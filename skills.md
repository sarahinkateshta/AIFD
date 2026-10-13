# Skills: Undulating Kinetic Wave & Optical Grid Poster Engine

A clear, comprehensive guide detailing the design principles, typography, mathematical grid, geometric modules, and procedural rules behind the optical wave poster.

---

## 1. Visual Mechanics & Design Influences

* **The Optical Illusion (Funhouse Mirror):** Text and geometric elements bend, compress, and stretch across a dynamic wave surface, giving the impression of viewing flat shapes wrapped around a 3D curve. Elements tilt toward or away from the viewer to simulate optical depth and perspective foreshortening.
* **Movement Roots:** Merges 1970s psychedelic kinetic geometry, 1960s Optical Art (Op-Art inspired by Victor Vasarely), and experimental Swiss typography (Wolfgang Weingart / Willi Kunz legacy).
* **Negative Space Treatment:** Open voids and wide margins are avoided. When text lines run short, procedural geometric shapes (stars, dots, pill capsules) step in to balance line density and maintain continuous rhythm.

---

## 2. Typographic Rules & Hierarchy

All fonts are sourced from Google Fonts:

* **Primary Latin Display & Headline Font:** **Sora** (Weight: 700 Bold or 800 ExtraBold)
  * *Role:* High-impact display headlines (Tier 1: "AFISHA PICNIC", "AFTERPARTY") as well as mid-tier lineup bands and repeating "DJ-SET" badges.
  * *Attributes:* Wide geometric grotesque construction, circular counters, and structural stability that holds up under extreme vector distortion.
* **Cyrillic Sub-Badge Font:** **JetBrains Mono** (Weight: 700 Bold or 800 ExtraBold)
  * *Role:* Russian sub-badge copy (Tier 2 Sub: «ПИКНИК «АФИШИ»).
  * *Attributes:* Native, first-class Cyrillic glyph support with a dense, blocky, industrial weight that pairs cleanly with the geometric Latin display rows.
* **Footer Utility Font:** **Sora** (Weight: 400 Regular or 500 Medium)
  * *Role:* Tier 3 metadata (website URL, venue street address).
  * *Attributes:* Clean, un-distorted legibility at small scale.

### Typographic Hierarchy Matrix

| Level | Content | Typeface | Case | Tracking | Distortion |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Tier 1 (Primary)** | Event Title & Date/Time | Sora (Bold / ExtraBold) | 100% UPPERCASE | Wide (+0.05em to +0.08em) | Maximum wave amplitude |
| **Tier 2 (Secondary)** | Artist Lineup & "DJ-SET" Badges | Sora (Bold) | 100% UPPERCASE | Medium (+0.03em) | Coordinated wave track |
| **Tier 2 Sub (Cyrillic)** | Russian Event Subtitle | JetBrains Mono (Bold) | 100% UPPERCASE | Compact | Integrated in wave crest |
| **Tier 3 (Utility)** | URL & Street Address | Sora (Regular / Medium) | 100% UPPERCASE | Wide (+0.12em) | **None** (Strictly flat & anchored) |

---

## 3. Mathematical Grid & Wave System

* **Canvas Ratio:** Standard DIN poster ratio (1:1.414 / A-series, e.g., A1, A2, A3).
* **Matrix Architecture:**
  * **Rows:** 12 tracking bands (8 primary text lines interleaved with 4 geometric filler bands).
  * **Columns:** 3 vertical lanes (Left, Center, Right) across an 8-beat modular rhythm.
* **Wave Displacement Formula:**
  $$\text{Baseline: } y(x) = y_0 + A \cdot \sin(2\pi f x + \phi)$$
  * **Amplitude ($A$):** 6% to 10% of total canvas height.
  * **Frequency ($f$):** 1.5 to 2.0 complete wave cycles across the canvas width.
* **Local Glyph Transformations:**
  * Letters do not sit upright on the curve; they rotate tangent to the wave slope ($\theta = \arctan(y'(x))$).
  * Vertical scaling modulates dynamically between $0.75\times$ (compression in troughs) and $1.3\times$ (expansion at crests) to simulate 3D foreshortening.
* **Margins:** Compact margins (3% to 4% of canvas width) produce an edge-to-edge, full-bleed typographic field.

---

## 4. Geometric Filler Module System

When text does not span the entire width of an undulating band, procedural filler modules must occupy the remaining units:

* **Diamond Stars (4-Point Sparks):** Pinched concave quadrilaterals utilized as focal line separators and full-width ambient rhythmic rows.
* **Solid Discs & Ellipses:** Round dots used as word breaks (e.g., separating artist names and the repeating "DJ-SET" token).
* **Semicircle Moons (D-Shapes):** Sliced semicircle discs arranged in repetitive sequence (5 to 7 units) indicating directional kinetic flow.
* **Vertical Pill Capsules:** Compressed vertical ovals positioned in pinched zones to exaggerate vertical curvature.

---

## 5. Color Palette & Materiality

* **Background:** Deep Solid Black (`#000000` or `#050505`).
* **Foreground Ink:** Monochromatic Platinum / Cool Silver-Gray (`#C8CBCD` to `#D6D8D9`).
* **Strict Duotone Rule:** Strictly two-tone contrast. No gradients, drop shadows, outlines, or color accents. Depth derives solely from positive/negative area balance and vector warping.

---

## 6. Procedural Layout Constraints ("Never" Rules)

1. **NEVER use lowercase characters** in the primary undulating rows.
2. **NEVER leave wide empty gutters:** If text runs short on an undulating line, fill the remaining segment with matching geometric glyphs (stars, half-moons, or dots).
3. **NEVER curve the baseline while keeping letters upright:** Letters must rotate and shear along the normal/tangent vector of the curve.
4. **NEVER introduce colored inks or soft drop-shadows:** Optical depth must remain purely vector-based and high-contrast.
5. **NEVER deform the micro metadata:** Corner venue info and website URLs must stay flat, un-warped, and anchored at the bottom margin.
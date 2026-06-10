# Bodrum Facade Elements Dataset

## Abstract
This study investigates whether the original buildings in Bodrum, Muğla—a region known for its distinct local architectural image—form the expected pattern. We examine the concept of the "Bodrum house," which began as a cultural tradition and was later protected by regulations regarding the number of floors, facade materials, and window frame colors. By focusing specifically on areas where original structures are preserved, we transform the facades of these "white and stone houses with blue or white frames" into two-dimensional, simple yet expressive icons to observe their similarities. In this way, we can explore the answer to the question, "Is Bodrum's original architectural texture truly iconic enough to be called a 'Bodrum house'?" while simultaneously taking a look at the city's past and authentic architectural fabric from a single source.

## Research Question
How do the dimensions, materials, and bounding box properties of Bodrum traditional house facade elements vary spatially, and what is the statistical distribution of frame-to-jamb (doğrama/söve) ratios across different geographical coordinates?

---

## Narrative & Design Strategy

### 1. Narrative & Core Message
* **Narrative:** This project examines the evolution of the "Bodrum house" from a cultural tradition to a regulated architectural identity, testing the consistency of its visual iconicity.
* **Core Message:** We empirically demonstrate that Bodrum’s architecture follows a specific geometric constraint; our data validates a prevalent "jamb-to-frame" ratio, confirming that the architectural texture is indeed iconic.

### 2. Target Audience & Design Rationale
* **Target Audience:** Architects, researchers working on Bodrum’s urban fabric, and enthusiasts of traditional architecture.
* **Design Rationale:** * **Page 1:** Data sources and spatial distribution of preserved heritage sites.
    * **Page 2:** Scatter plot analysis for granular investigation of facade dimensions.
    * **Page 3:** Holistic visualization for morphological observation.
* **Iconography:** 2D icons were chosen to simplify complex visual information, allowing for a clear, facade-focused morphological analysis.

### 3. Critical Reflection & Insights
* **Critical Evaluation:** We observed that commercial conversions often deform original architectural proportions. Conversely, the preservation of traditional textures in newer builds indicates either strict adherence to regulations or high architectural sensitivity.
* **Unexpected Patterns:** Some stone buildings utilize cornerstones (köşe taşı) to mimic jambs, suggesting that these elements serve both structural and visual functions.
* **Reflection:** The concentration of jamb/frame dimensions within a specific range confirms a standardized "morphological language" in Bodrum architecture.

---

## Data Collection & Ethics
* **Methodology:** This study relies on manual annotation (makesense.ai) and on-site documentation, adhering to academic ethical standards. No automated web scraping (scraping) was utilized.
* **Time Scope:** The dataset covers preserved traditional structures in Bodrum as of 2026.
* **Data Reliability:** All data points underwent manual validation and coordinate cross-referencing to ensure high precision.

## Project Specifications & Data Quality
* **Total Records:** 700 facade elements.
* **Unique Buildings:** 84 preserved traditional structures.
* **Data Consistency:** Jamb ratio formula logic corrected; coordinate errors rectified.
* **Missing Data & Bias:** Non-functional frames were excluded; the dataset exhibits a spatial bias toward historical neighborhoods, which was a conscious decision to capture the "original texture."

## Data Fields
| Field | Description |
| :--- | :--- |
| `label_name` | Classification of the architectural element |
| `bbox_x/y/w/h` | Pixel-level geometry coordinates |
| `image_name/w/h` | Source file metadata and resolution |
| `malzeme` | Material composition (e.g., stone, stucco) |
| `Enlem/Boylam` | Decimal Degrees (DD) for spatial mapping |

## Files
* `dataset.pkl`, `dataDictionary.json`, `metadata.json`, `requirements.txt`, `README.md`

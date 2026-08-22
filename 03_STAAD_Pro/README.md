# STAAD.Pro – Structural Analysis and Design

This section contains the structural analysis and design of the G+1 residential building performed using STAAD.Pro.

## Software Used
- STAAD.Pro 2026

## Design Codes
- IS 456:2000 – Plain and Reinforced Concrete
- IS 1893:2016 – Criteria for Earthquake Resistant Design

## Structural Components
The structural model includes:
- Columns (300 x 300 mm)
- Beams (230 x 450 mm)
- Slabs (152.4 mm thick)
- Supports (Fixed)
- Load combinations

## Material Properties
- Concrete Grade: M25
- Steel Grade: Fe500 (Main and Secondary reinforcement)

## Analysis
The building structure was analyzed for different loading conditions, including:
- Dead Load (self-weight, slab load, wall load)
- Live Load
- Seismic Load in X direction (Positive and Negative)
- Seismic Load in Z direction (Positive and Negative)
- Load Combinations as per IS 456 and IS 1893 (14 combinations)

The building is located in Seismic Zone III (Z = 0.16) as per IS 1893:2016.

## Files

### Model and Result Files
- `G+1_House_Model.std` – STAAD.Pro structural model
- `Analysis_Results.pdf` – Structural analysis results
- `Design_Results.pdf` – RCC design results

### Structural Diagrams
- `3D_view_Staad_structure.png` – 3D structural model view
- `01_Dead_Load.png` – Dead load diagram
- `02_Live_Load.png` – Live load diagram
- `03_Seismic_X.png` – Seismic load in +X direction
- `04_Seismic_X_Negative.png` – Seismic load in -X direction
- `05_Seismic_Z.png` – Seismic load in +Z direction
- `06_Seismic_Z_Negative.png` – Seismic load in -Z direction
- `07_DL_LL_EQX_Combination.png` – Load combination diagram (DL+LL+EQX)
- `08_DL_LL_EQZ_Combination.png` – Load combination diagram (DL+LL+EQZ)

## Description

The structural model of the G+1 residential building was developed in STAAD.Pro. Appropriate material properties, member dimensions, supports and loading conditions were assigned to the structure. The building was analyzed for gravity loads (dead and live load) as well as seismic loads as per IS 1893:2016, considering the building's location in Seismic Zone III.

The model was analyzed to obtain forces, moments, displacements and other structural responses under 14 different load combinations. The structural members (beams and columns) were then designed as per IS 456:2000 Limit State Method based on the governing analysis results, and the required reinforcement details were obtained.

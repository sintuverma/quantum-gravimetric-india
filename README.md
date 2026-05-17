# Quantum Gravimetric AI v4.1
## India Underground Structure Mapping System

### Data Sources
1. Birmingham Quantum Gravimeter Lab (UK)
2. EGM2008 Satellite Geoid (466 MB)
3. ICGEM EGM2008 India Grid (87,591 pts)
4. LITHO1.0 Crustal Model (1,012 nodes)
5. Copernicus COP30 DEM (30m, Himalaya)

### Model Results
| Model | RMSE | R² |
|-------|------|-----|
| Himalaya | 4.0108 mGal | 0.999478 |
| Plains   | 1.0443 mGal | 0.999898 |
| Oceanic  | 2.1469 mGal | 0.999518 |
| Tunnel Classifier | — | Acc=59.4% |
| Depth Estimator | 512 m | 0.5100 |

### Files
- models/ : Trained PyTorch models (.pth)
- visuals/: 6 professional figures (.png)
- csv/    : Predictions + sensor data
- results/: Master results table

### Classification: Proof of Concept
Date: May 2026

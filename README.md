# Geographic Data Repository for Igbo Community Atlas

This repository contains all geospatial vector layers (GeoJSON) for Nigeria and the Igbo homeland.

## 📦 Files in this Repository

| File | Description | Size |
| :--- | :--- | :--- |
| **`populated_places.geojson`** | All settlements, cities, towns, villages, and hamlets across Nigeria | ~186.5 MB |
| **`waterways.geojson`** | River networks, streams, canals, and tributaries | ~151.9 MB |
| **`points_of_interest.geojson`** | Cultural locations, markets, shrines, town halls, schools, amenities | ~41.9 MB |
| **`nigeria_lga_boundaries.geojson`** | 774 LGA boundaries across Nigeria | ~5.7 MB |
| **`nigeria_state_boundaries.geojson`** | 36 States + FCT administrative boundaries | ~1.7 MB |
| **`nga_admin3.geojson`** | Ward-level boundaries (Admin level 3) | ~2.5 MB |
| **`nga_admin3_em.geojson`** | Ward-level boundaries with extended metadata | ~2.8 MB |
| **`nga_admin2.geojson`** | HDX LGA boundaries | ~5.8 MB |
| **`nga_admin2_em.geojson`** | HDX LGA boundaries with extended metadata | ~6.3 MB |
| **`nga_admin1.geojson`** | HDX State boundaries | ~1.7 MB |
| **`nga_admin1_em.geojson`** | HDX State boundaries with extended metadata | ~2.1 MB |
| **`nga_admin0.geojson`** | National outline (Admin 0) | ~270 KB |
| **`nga_admin0_em.geojson`** | National outline with extended metadata | ~666 KB |
| **`nga_admincapitals.geojson`** | Administrative capital coordinates | ~588 KB |
| **`nga_adminlines.geojson`** | Boundary demarcation vectors | ~4.5 MB |
| **`nga_adminlines_em.geojson`** | Boundary demarcation vectors with extended metadata | ~4.9 MB |
| **`nga_adminpoints.geojson`** | Administrative centroids | ~1.4 MB |
| **`nga_senatorialdistricts.geojson`** | Senatorial district boundaries | ~2.6 MB |
| **`nga_senatorialdistricts_em.geojson`** | Senatorial district boundaries with extended metadata | ~3.1 MB |

## 🚀 Pushing to GitHub (Large File Storage Notice)
Files exceeding **100 MB** (`populated_places.geojson` and `waterways.geojson`) require **Git LFS**:

```bash
# If you don't have git-lfs installed yet, install it once:
git lfs install

# In this repository:
git init
git lfs track "*.geojson"
git add .gitattributes
git add .
git commit -m "feat: initial commit of Nigeria & Igbo atlas geospatial data layers"
git branch -M main
git remote add origin <YOUR_GITHUB_REPO_URL>
git push -u origin main
```

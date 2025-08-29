# PhotonLabeling v1.0

PhotonLabeling is a lightweight desktop tool for labeling **photon point cloud data**, designed for scientific research and data preprocessing tasks. It provides interactive functions such as zoom, pan, rectangular/ellipse selection, point editing, and data export.

---

## 🌟 Features

- ✅ Load CSV-format photon point cloud data
- ✅ Interactive visualization (pan, zoom, aspect-ratio locking)
- ✅ Rectangle, ellipse, and line-based selection tools
- ✅ Point-level editing and labeling
- ✅ Real-time operation logging
- ✅ Export labeled results to CSV

---

## 📸 Main Window
![Selection Demo](docs/PhotonLabeling.gif)

---

## 📂 File Format

Input file format should be a CSV file with **X** and **Y** coordinates. You can select the corresponding column numbers when loading data.

Example:

```csv
x_coord,y_coord,label
123.4,456.7,0
125.1,458.3,0
...

## 📖 Citation

If this software is useful for your research, please cite the following paper:

Shi, Z., Li, J., Yang, Z., Long, H., Cui, H., Zhao, S., Li, X., Li, Q. (2025). A Linear Feature-Based Method for Signal Photon Extraction and Bathymetric Retrieval Using ICESat-2 Data. Remote Sensing, 17(16), 2792. https://doi.org/10.3390/rs17162792

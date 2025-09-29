# 🚘 BMW 3D Sales Dashboard

An interactive **Power BI Dashboard** with integrated **3D BMW car models**, combining advanced analytics and immersive visual experiences.

---

## 🌟 Highlights

✅ **Dynamic 3D Car Models** powered by **Three.js**
✅ **Interactive Dashboard** for exploring BMW sales data
✅ **Transmission, Region, Price Segment & Yearly Trends**
✅ **50,000+ Records** with detailed attributes (Model, Price, Sales Volume, Transmission, Color, Engine Size, Fuel Type, Region, Year)

---

## 🖼️ Dashboard Preview

<p align="center">
  <img src="./assets/dashboard_preview.png" alt="BMW 3D Dashboard Preview" width="800"/>
</p>  

*(Replace with your actual dashboard screenshot at `assets/dashboard_preview.png`)*

---

## 🛠️ Tech Stack

* **Power BI** → Dashboard design & visualization
* **Three.js** → 3D rendering of BMW car models
* **GLTFLoader** → Loading `.glb` BMW 3D models
* **OrbitControls** → Rotate, zoom & pan 3D cars
* **GitHub Pages** → Hosting 3D models & viewer
* **HTML Content Viewer (Custom Visual)** → Embedding 3D viewer in Power BI

---

## ⚙️ How It Works

1️⃣ BMW 3D models (`.glb`) are hosted on **GitHub Pages**
2️⃣ A custom `bmw_viewer.html` loads models with **Three.js**
3️⃣ Power BI uses **HTML Content Viewer** to embed this page
4️⃣ A **Model Slicer** in Power BI changes the displayed car dynamically

---

## 📂 Project Structure

```
BMW-3D-Dashboard/
│
├── PowerBI/
│   └── BMW_Sales_Dashboard.pbix      # Power BI dashboard file
│
├── Models/
│   ├── bmw_m850.glb
│   ├── bmw_x5.glb
│   ├── bmw_i3.glb
│   └── ...
│
├── Viewer/
│   └── bmw_viewer.html               # HTML + JS script to render models
│
├── assets/
│   └── dashboard_preview.png         # Dashboard preview image
│
└── README.md                         # Documentation
```

---

## 🚀 Future Enhancements

✨ **Car Animations** (doors opening, auto-rotate)
✨ **Neon Theme** for futuristic Power BI UI
✨ **Highlight Best-Selling Models** with glow effects
✨ **Compressed 3D Models** for faster loading

---

## 👤 Author

**Shanmukha Sai Bada**
🔹 Power BI Developer | Data Analyst
🔗 [GitHub](https://github.com/shanmukhsaibada) | [LinkedIn](https://www.linkedin.com/in/shanmukha-sai-bada/)

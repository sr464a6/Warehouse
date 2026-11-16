<div align="center">

<!-- Animated 3D Wave Header with Blinking Neon Effect -->
<img src="https://capsule-render.vercel.app/api?type=shark&color=0:0f172a,50:1e3a8a,100:06b6d4&height=200&section=header&text=📦%20WAREHOUSE%20INVENTORY&fontSize=38&fontColor=38bdf8&animation=twinkling&fontAlignY=35&desc=Smart%20Stock%20%E2%80%A2%20Asset%20Valuation%20%E2%80%A2%20Automated%20Reporting&descAlignY=60&descSize=18&descColor=e2e8f0" width="100%" />

<!-- Animated Rainbow Neon Line -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<br/>

<!-- 3D Tech Stack Icons -->
<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=php,mysql,html,css,js,bootstrap&perline=6" alt="Tech Stack" />
</a>

<br/><br/>

[![PDO Security](https://img.shields.io/badge/🔒_Security-PDO_Prepared_Statements-06b6d4?style=for-the-badge&labelColor=0f172a)](#)
[![Responsive](https://img.shields.io/badge/📱_Interface-Mobile_%26_Desktop-3b82f6?style=for-the-badge&labelColor=0f172a)](#)
[![Environment](https://img.shields.io/badge/⚡_Server-XAMPP_Apache-f97316?style=for-the-badge&labelColor=0f172a)](#)

</div>

---

<!-- SPLIT-SCREEN HERO SECTION -->
<table>
  <tr>
    <td width="60%" valign="middle">
      <h2>📦 Warehouse Inventory System</h2>
      <p>A simple web-based inventory management system built with <b>PHP</b> and <b>MySQL</b>.</p>
      <p>This application is designed to help manage warehouse inventory, including product data, stock quantities, prices, inventory value, and printable inventory reports.</p>
      <hr/>
      <b>🛠️ Core Technologies:</b><br/>
      <code>PHP</code> • <code>MySQL</code> • <code>PDO</code> • <code>HTML5</code> • <code>CSS3</code> • <code>JavaScript</code> • <code>Bootstrap CDN</code>
    </td>
    <td width="40%" align="center" valign="middle">
      <!-- Animated Coding / Data Processing GIF -->
      <img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="100%" style="border-radius: 12px;" alt="Warehouse System Animation" />
    </td>
  </tr>
</table>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## ✨ Features (Bento Grid View)

<table>
  <tr>
    <td width="33%" valign="top">
      <h3 align="center">📊 Smart Dashboard</h3>
      <ul>
        <li>📊 Inventory dashboard</li>
        <li>📉 Low-stock detection</li>
        <li>💰 Automatic inventory value calculation</li>
        <li>🖥️ Desktop-friendly dashboard</li>
      </ul>
    </td>
    <td width="33%" valign="top">
      <h3 align="center">📦 Stock Control</h3>
      <ul>
        <li>📦 Product inventory management</li>
        <li>➕ Add products</li>
        <li>✏️ Edit products</li>
        <li>🗑️ Delete products</li>
        <li>🔎 Search inventory</li>
      </ul>
    </td>
    <td width="33%" valign="top">
      <h3 align="center">🖨️ Reports & UI</h3>
      <ul>
        <li>📋 Inventory reports</li>
        <li>🖨️ Print reports</li>
        <li>📱 Responsive mobile interface</li>
      </ul>
    </td>
  </tr>
</table>

---

## 📊 Main Pages Architecture

```mermaid
graph LR
    A((👤 User)) --> B[📊 /beranda.php<br/>Dashboard]
    A --> C[📦 /index.php<br/>Inventory]
    A --> D[📋 /laporan.php<br/>Reports]

    B --> B1(Total product types & stock)
    B --> B2(Total inventory value)
    B --> B3(Low-stock & Recent products)

    C --> C1(Add, Edit, Delete products)
    C --> C2(Search products)
    C --> C3(View stock & inventory value)

    D --> D1(Complete inventory report)
    D --> D2(Print function)

    style A fill:#06b6d4,stroke:#0f172a,stroke-width:2px,color:#000
    style B fill:#1e3a8a,stroke:#38bdf8,stroke-width:2px,color:#fff
    style C fill:#1e3a8a,stroke:#38bdf8,stroke-width:2px,color:#fff
    style D fill:#1e3a8a,stroke:#38bdf8,stroke-width:2px,color:#fff

```

| Route | Page Name | Core Functionality |
| --- | --- | --- |
| **`/beranda.php`** | **Dashboard** | Displays: Total product types, Total stock, Total inventory value, Low-stock products, and Recently added products. |
| **`/index.php`** | **Inventory** | Used to: Add products, Edit products, Delete products, Search products, View stock, and View inventory value. |
| **`/laporan.php`** | **Reports** | Displays a complete inventory report and provides a print function. |

---

## ⚡ Interactive System Blueprint

*(Click the arrows below to expand each technical section)*

**Database:** `gudang` | **Main table:** `barang`

| Column | Description |
| --- | --- |
| **`id`** | Product ID |
| **`nama_barang`** | Product Name |
| **`jumlah`** | Stock Quantity |
| **`harga_per_pcs`** | Price Per Unit |
| **`created_at`** | Creation Date |
| **`updated_at`** | Last Update Date |

---

## 🔐 Security & 📱 Responsive Design

---

## 📄 License

This project was created for educational and inventory management purposes.

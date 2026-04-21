# Supply Chain Command Center

**Dashboard quản lý chuỗi cung ứng chuyên nghiệp** – Dành cho Supply Chain Analyst, Purchaser & Sourcing Specialist.

Một công cụ **single-file** mạnh mẽ, chạy hoàn toàn trên trình duyệt, không cần server, không tốn phí.

![Dashboard Preview](https://nhuthao52000.github.io/1st-portfolio-scm/preview.jpg)  
*(Bạn có thể thay link preview sau khi up ảnh screenshot)*

### 🌐 Link Demo
**https://nhuthao52000.github.io/1st-portfolio-scm/**

---

### ✨ Tính năng nổi bật

- **Dashboard Live** với KPI realtime (OTD, Cost Saving, QBR Score, Delayed PO…)
- **Import dữ liệu từ ERP** (SAP, Oracle, Excel) qua CSV – hỗ trợ Upsert
- **Theo dõi Purchase Order** chi tiết (Open / Delayed / On-Time)
- **QBR Scorecard** tự động tính điểm có trọng số
- **Sourcing / RFQ** so sánh báo giá ≥3 nhà cung cấp
- **Logistics & Shipment** tracking ETD/ETA
- **Contract Management** + cảnh báo hết hạn
- **Daily Checklist** + Email Templates sẵn
- **Auto Insights & Critical Alerts**
- **Reports** tự động (Weekly Snapshot & Monthly Report)
- **Backup / Restore** toàn bộ dữ liệu bằng JSON
- **Giao diện đẹp**, dark/light friendly, responsive

---

### 🚀 Cách sử dụng nhanh

1. Truy cập link demo ở trên
2. Vào **Settings** → điền tên công ty & tên Analyst
3. Vào **Data Hub & ERP** → Import Suppliers trước
4. Import tiếp **Purchase Orders** từ ERP (SAP ME2L/ME2M hoặc Oracle)
5. Dashboard sẽ tự động cập nhật tất cả biểu đồ và alert

**Mẹo**: Import 2 lần/ngày (sáng 8:30 & chiều 16:00) để dữ liệu luôn chính xác.

---

### 📥 Hướng dẫn Import từ ERP

- Xuất file từ SAP/Oracle → lưu dạng **CSV UTF-8**
- Vào **Data Hub** → chọn entity → Import CSV
- App sẽ tự map cột và preview trước khi lưu
- Hỗ trợ **Upsert** (không làm mất dữ liệu cũ)

Có sẵn **Template CSV** cho từng bảng (nhấn nút Template trong Data Hub).

---

### 💾 Backup & Restore dữ liệu

- **Backup**: Vào Data Hub → **⬇ Backup JSON**
- **Restore**: Vào Data Hub → **⬆ Restore JSON**
- Nên backup định kỳ (1–2 lần/tuần)

**Lưu ý**: Dữ liệu được lưu trong trình duyệt của bạn. Nếu xóa cache hoặc đổi máy thì phải restore từ file JSON.

---

### 🛠 Công nghệ sử dụng

- HTML5 + CSS3 + Vanilla JavaScript
- Chart.js (biểu đồ)
- PapaParse (đọc CSV)
- LocalStorage (lưu dữ liệu)
- GitHub Pages (hosting miễn phí)

---

### ⚠️ Hạn chế

- Dữ liệu chỉ lưu trên trình duyệt (không đồng bộ giữa các thiết bị)
- Phù hợp cho cá nhân hoặc team nhỏ (< 5.000 records)
- Không có đăng nhập đa người dùng
- Phải tự import CSV từ ERP (không tự động kết nối)

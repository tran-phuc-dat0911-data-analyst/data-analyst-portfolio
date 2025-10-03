# 📊 Insurance Analytics — Portfolio Project
**Sinh viên:** Trần Phúc Đạt  
**Mô tả:** Dự án mô phỏng hệ thống phân tích dữ liệu bảo hiểm xe cơ giới: Data Dictionary, Data Model, dữ liệu test, SQL DDL, ví dụ truy vấn và dashboard Power BI.

## Nội dung repo
- `01_Project_Overview/` — Tổng quan dự án, mục tiêu nghiệp vụ (tham khảo báo cáo thực tập). :contentReference[oaicite:3]{index=3}
- `02_DataDictionary/` — Data Dictionary (danh sách bảng Fact & Dim). :contentReference[oaicite:4]{index=4}
- `03_DataModel/` — Hình ảnh model tổng thể (Star Schema). :contentReference[oaicite:5]{index=5}
- `04_SQL/` — DDL tạo bảng + sample queries.
- `05_SampleData/` — Script Python sinh dữ liệu demo & CSV mẫu.
- `06_PowerBI/` — File .pbix (dashboard demo).
- `07_Reports/` — Hình ảnh screenshot của báo cáo đã làm.

## Quick start
1. Clone repo:  
   `git clone https://github.com/<username>/data-analyst-portfolio-insurance.git`
2. (Tùy chọn) Tạo database local (Postgres/MySQL) và chạy file `04_SQL/ddl_create_tables.sql`.
3. Sinh dữ liệu demo: `python 05_SampleData/generate_sample_data.py`
4. Import CSV vào DB hoặc connect Power BI tới CSV rồi build dashboard.

## Nguồn
Dự án dựa trên nội dung báo cáo thực tập (Data Dictionary, Data Model, templates báo cáo). :contentReference[oaicite:6]{index=6}

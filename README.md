# 🎯 Building a Data Warehouse for CGV Cinema Ticket Sales

## 🌐 Links

- 🔗 **Introduction**: https://drive.google.com/file/d/1CiB49rq8bChZeInPZb-gGbc-d8-gQFgD/view?usp=sharing
  
- 🧾 **Report**: https://drive.google.com/file/d/19-TMFUjoW_9xysrArHzSbMGF-s9-5mic/view?usp=sharing
  
- 📁 **Other Sources**: https://drive.google.com/drive/folders/131JhWXXTZ4hHe9h1ReOJqcZsTOukfl5X?usp=sharing

---

## 📝 I. Overview

Dự án xây dựng hệ thống **Data Warehouse** và phân tích dữ liệu kinh doanh nhằm hỗ trợ doanh nghiệp đánh giá hiệu quả hoạt động theo chi nhánh và khu vực.
Kết quả giúp cung cấp insight phục vụ việc ra quyết định chiến lược.

---

## ❗II. Problem

Doanh nghiệp gặp khó khăn trong việc:
- Dữ liệu phân tán từ nhiều nguồn (bán vé, khách hàng, phim,...)
- Khó theo dõi hiệu quả kinh doanh theo từng chi nhánh/khu vực
- Thiếu hệ thống phân tích KPI tổng thể
👉 Cần một hệ thống dữ liệu tập trung để hỗ trợ **Business Intelligence & Analytics**

---

## 🛠️ III. Approach / Methodology

**1. Data Warehouse Development**
- Xây dựng Data Warehouse để tích hợp và chuẩn hóa dữ liệu từ nhiều nguồn
- Thiết kế ETL logic (Extract – Transform – Load)
  
**2. Data Modeling**
- Thiết kế dimensional model:
  - Fact table: Doanh thu, số lượng vé
  - Dimension tables: Khách hàng, phim, thời gian, chi nhánh
- Áp dụng Snowflake Schema để tối ưu lưu trữ và phân tích

**3. OLAP Cube**
- Xây dựng OLAP Cube SSAS
- Hỗ trợ truy vấn dữ liệu đa chiều:
  - Theo thời gian
  - Theo khu vực
  - Theo sản phẩm (phim)
  
**4. Data Analysis (MDX)**
- Viết và tối ưu truy vấn MDX để:
  - Phân tích doanh thu
  - Đánh giá KPI
  - So sánh hiệu suất giữa các khu vực
- Thực hiện drill-down / slice & dice dữ liệu

---

## 🚀 IV. Results & Impact

- Xác định các chi nhánh hoạt động kém hiệu quả
- Hỗ trợ đề xuất cải thiện chiến lược kinh doanh theo khu vực
- Cung cấp insight dựa trên dữ liệu giúp tối ưu vận hành và phân bổ nguồn lực


## 🛠️ V. Tech Stack

- SQL Server
- SSMS (SQL Server Management Studio)
- SSAS (SQL Server Analysis Services)
- MDX

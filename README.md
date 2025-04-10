# Supply Chain Dashboard 📦📊

## 📌 Overview
Dự án này là một dashboard được xây dựng bằng Power BI nhằm phân tích hiệu suất chuỗi cung ứng từ nhiều góc độ như doanh thu, lợi nhuận, đơn hàng, thời gian giao hàng và tỷ lệ hoàn trả. Mục tiêu là hỗ trợ việc ra quyết định trong quản lý logistics và tối ưu vận hành.

## 🧩 Dashboard Includes
Dashboard gồm **3 trang chính**:

### 1. **Overview**
- Tổng quan doanh thu (Revenue), lợi nhuận (Profit), số đơn hàng và thời gian giao hàng trung bình.
- Biểu đồ xu hướng doanh thu & lợi nhuận theo tháng.
- Doanh thu phân theo **phân khúc khách hàng** và **loại sản phẩm**.
- Bản đồ doanh thu theo **bang** tại Hoa Kỳ.
- Biểu đồ số ngày giao hàng trung bình theo tháng.

### 2. **Delivery & Return**
- Tỷ lệ giao hàng trễ và tỷ lệ hoàn trả theo từng **phương thức vận chuyển** (Ship Mode).
- Phân tích tác động của việc giao hàng trễ đến tỷ lệ hoàn trả.
- Biểu đồ số ngày giao hàng trung bình theo **vùng địa lý**.
- Biểu đồ Sankey phân tích mối quan hệ giữa Ship Mode → Category → Sub-category.

### 3. **Sales Performance**
- Tỷ suất lợi nhuận theo từng **dòng sản phẩm** và **năm**.
- Doanh thu & lợi nhuận theo **customer segment**.
- Top khách hàng mang lại doanh thu cao nhất.
- Giá trị đơn hàng trung bình và số lượng khách hàng.

## 🛠️ Technologies Used
- **Power BI Desktop**
- **Excel (.xlsx)** – nguồn dữ liệu đầu vào
- **DAX** – để tính toán các chỉ số nâng cao như Profit Margin, Return Rate, AVG Delivery Days

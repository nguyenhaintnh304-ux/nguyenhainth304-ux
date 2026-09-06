# NGUYỄN QUỐC HẢI - DATA ANALYST PORTFOLIO

Xin chào! Tôi là Nguyễn Quốc Hải, là một Data Analyst với đam mê khai thác các tập dữ liệu thực tế và chuyển hóa chúng thành các khuyến nghị chiến lược giúp doanh nghiệp tối ưu hóa doanh thu, cải thiện vận hành và nâng cao trải nghiệm khách hàng.

Dưới đây là Portfolio tổng hợp các dự án phân tích dữ liệu nổi bật của tôi, được xây dựng theo tiêu chuẩn doanh nghiệp (End-to-End) từ khâu xử lý dữ liệu kỹ thuật đến trực quan hóa và báo cáo cấp quản lý.

---

## Công cụ & Kỹ năng

*   **Ngôn ngữ:** Python (Pandas, NumPy), SQL Server.
*   **Trực quan hóa dữ liệu:** Power BI (DAX, Power Query), Excel.
*   **Kỹ năng phân tích:** phân tích hành vi khách hàng, phân tích thị trường, mô hình hóa dữ liệu, kỹ thuật đặc trưng.
*   **Truyền thông kinh doanh:** Soạn thảo báo cáo, thiết kế Slide thuyết trình cấp quản lý.

---

## Các Dự Án Tiêu Biểu

### Dự án 1: E-Commerce Online Sales Analysis
**Giải pháp tối ưu doanh thu và cá nhân hóa chính sách giá dựa trên 1.000 giao dịch thương mại điện tử.**

<p align="center">
  <!-- HƯỚNG DẪN: Thay thế đường dẫn ảnh dưới đây bằng ảnh dashboard Power BI của bạn -->
  <img src="https://github.com/nguyenhaintnh304-ux/E-Commerce-Online-Sales-Analysis/blob/main/images/dashboard.png?raw=true" width="85%" alt="E-Commerce Sales Analytics Dashboard">
</p>

*   **Bối cảnh:** Một doanh nghiệp thương mại điện tử cần theo dõi doanh số, đánh giá hiệu quả sản phẩm và tìm kiếm các cơ hội tăng trưởng doanh thu theo chu kỳ thời gian và phân bổ thị trường.
*   **Mục tiêu:** Phân tích dữ liệu giao dịch để tìm ra các điểm nghẽn doanh thu, sự khác biệt giữa sản lượng bán ra và giá trị mang lại, đồng thời đo lường mức độ chịu chi (AOV) của từng thành phố.
*   **Quy trình:**
    *   Import dữ liệu trên **SQL Server**.
    *   Thực hiện các truy vấn phân tích chuyên sâu trên SQL Server.
    *   Thiết kế dasboard trên **Power BI** với tông màu hồng cánh sen hiện đại, tích hợp các thẻ KPI chính (1,000 khách hàng, $27.62M doanh thu) và bộ lọc theo tháng.
*   **Kết quả & Khuyến nghị Kinh doanh:**
    *   **Tập trung vào danh mục cốt lõi:** Ngành hàng Điện tử (Electronics) đóng góp tới **78.2% tổng doanh thu** ($21.61M), trong đó Laptop ($11.41M) và Tablet ($5.93M) là hai mũi nhọn tài chính. Khuyến nghị tối ưu hóa tồn kho và chính sách bảo hành riêng cho dòng sản phẩm này.
    *   **Chiến lược bán kèm thông minh (Cross-sell):** T-Shirt dẫn đầu tuyệt đối về sản lượng bán ra (259 đơn) nhưng đóng góp doanh thu thấp. Doanh nghiệp nên đóng gói combo T-Shirt + phụ kiện cao cấp để kích cầu mua sắm.
    *   **Tối ưu lịch marketing:** Doanh thu đạt đỉnh vào **Thứ Hai và Thứ Ba** (chiếm hơn 34% doanh thu tuần). Khuyến nghị đẩy mạnh các chương trình Flash Sale, quảng cáo và gửi email marketing vào các khung giờ vàng này.
    *   **Phân hóa chính sách giá (AOV) theo thành phố:** Khách hàng ở Bangalore và Kolkata cực kỳ chịu chi với giá trị đơn hàng trung bình (AOV) vượt trội (>34,000 USD/đơn), trong khi Hyderabad có AOV thấp nhất (<20,000 USD/đơn). Khuyến nghị chạy gói sản phẩm cao cấp tại Bangalore, Kolkata và chạy chương trình trợ giá, combo tiết kiệm tại Hyderabad, Ahmedabad để kích cầu.

👉 **Liên kết dự án:**
*   [Chi tiết dự án](https://github.com/nguyenhaintnh304-ux/E-Commerce-Online-Sales-Analysis)
*   [Dashboard](https://app.powerbi.com/links/2uwaSalKxi?ctid=948ae523-08bd-414e-a287-22da3e46c1eb&pbi_source=linkShare)
*   [Slide thuyết trình](https://docs.google.com/presentation/d/1Z34q1Pl6uk8ppeZQdUR1pjuQ5l4iia0b8kC_W9Jw4FI/edit?slide=id.p1#slide=id.p1)

---

### Dự án 2: Shopping Trends And Customer Behaviour
**Xây dựng quy trình ETL làm sạch dữ liệu tự động bằng Python và tối ưu hóa chính sách thành viên của khách hàng.**

<p align="center">
  <!-- HƯỚNG DẪN: Thay thế đường dẫn ảnh dưới đây bằng ảnh dashboard Power BI của bạn -->
  <img src="https://github.com/nguyenhaintnh304-ux/Shopping-Trends-And-Customer-Behaviour/blob/main/Images/dashboard.png" width="85%" alt="Customer Behavior Analytics Dashboard">
</p>

*   **Bối cảnh:** Ban giám đốc một chuỗi bán lẻ muốn hiểu rõ các yếu tố (độ tuổi, giảm giá, hình thức vận chuyển) tác động đến hành vi mua sắm lặp lại và quyết định đăng ký thành viên của khách hàng.
*   **Mục tiêu:** Làm sạch và chuẩn hóa dữ liệu thô bị khuyết thiếu, phân đoạn khách hàng theo mức độ trung thành và đề xuất giải pháp thúc đẩy chương trình thẻ thành viên.
*   **Quy trình:**
    *   Sử dụng **Python (Pandas)** trong Jupyter Notebook để khám phá dữ liệu.
    *   Chuẩn hóa tên cột sang định dạng `snake_case`, thực hiện kỹ thuật đặc trưng phân nhóm tuổi (`age_group` qua hàm `pd.qcut`) và số hóa cột tần suất mua hàng sang số ngày cụ thể.
    *   Import dữ liệu sạch từ Python vào **SQL Server**.
    *   Thực hiện các truy vấn phân tích chuyên sâu trên SQL Server.
    *   Xây dựng báo cáo **Power BI Dashboard** trực quan hóa tỷ lệ khách hàng đăng ký thành viên, doanh thu phân bổ theo nhóm tuổi và tích hợp hệ thống bộ lọc Button Slicers.
*   **Kết quả & Khuyến nghị Kinh doanh:**
    *   **Thúc đẩy Giao hàng nhanh (Express Shipping):** Mức chi tiêu trung bình của khách hàng lựa chọn hình thức Express Shipping cao hơn đáng kể so với Standard. Doanh nghiệp nên tối ưu hóa quy trình đóng gói và hợp tác sâu với các đơn vị vận chuyển hỏa tốc để thúc đẩy doanh số.
    *   **Cơ hội vàng chuyển đổi Thành viên:** Có tới **2.500 khách hàng mua sắm trên 5 lần nhưng chưa đăng ký thành viên** (chỉ có 958 người đã đăng ký). Điều này chứng tỏ gói đặc quyền thành viên hiện tại chưa đủ sức hấp dẫn. Đề xuất: Thiết lập chương trình tặng điểm thưởng gấp đôi và miễn phí vận chuyển cho đơn hàng thứ 6 trở đi nếu đăng ký thẻ thành viên.
    *   **Hướng tới đúng phân khúc tuổi chủ chốt:** Nhóm người trẻ (young adults) đóng góp doanh thu cao nhất hệ thống. Doanh nghiệp nên dịch chuyển ngân sách tiếp thị sang các kênh xã hội trẻ trung để tiếp cận tối đa tệp khách hàng tiềm năng này.

**Liên kết dự án:**
*   [Chi tiết dự án](https://github.com/nguyenhaintnh304-ux/Shopping-Trends-And-Customer-Behaviour)
*   [Dashboard](https://app.powerbi.com/links/Xy9Hy-o01f?ctid=948ae523-08bd-414e-a287-22da3e46c1eb&pbi_source=linkShare)
*   [Slide thuyết trình](https://docs.google.com/presentation/d/1Z34q1Pl6uk8ppeZQdUR1pjuQ5l4iia0b8kC_W9Jw4FI/edit?usp=sharing)

---

## Liên hệ 

*   **Email:** [nguyenhaintnh304@gmail.com](mailto:[nguyenhaintnh304@gmail.com)
*   **Số điện thoại:** [0967528361]

---
*Cảm ơn bạn đã dành thời gian ghé thăm Portfolio của tôi! Chúc bạn một ngày tuyệt vời.*

# Tổng quan dự án
## Mục tiêu dự án
Dự án phân tích dữ liệu khách hàng sử dụng thẻ tín dụng của một ngân hàng bao gồm những khách hàng vẫn đang sử dụng và khách hàng đã ngừng sử dụng nhằm mục đích hiểu rõ hành vi và đặc điểm của khách hàng để tối ưu hóa các chiến lược marketing, cải thiện trải nghiệm khách hàng, và tăng trưởng doanh thu cho ngân hàng. Phân tích dữ liệu sẽ giúp ngân hàng xác định các nhóm khách hàng tiềm năng, tối ưu hóa các dịch vụ và sản phẩm, từ đó xây dựng các chiến lược tiếp cận và duy trì khách hàng sử dụng thẻ tín dụng hiệu quả hơn.
## Công cụ và phương pháp sử dụng
Xử lý dữ liệu: Sử dụng Python (Pandas, NumPy) để thu thập và làm sạch dữ liệu.

Phân tích thống kê: Dùng các công cụ phân tích thống kê Python (SciPy, Statsmodels) để thực hiện các phép kiểm định và phân tích mô tả.

Học máy (Machine Learning): Sử dụng các thuật toán học máy như phân tích hồi quy để phân tích và dự đoán hành vi khách hàng.

Trực quan hóa dữ liệu: Sử dụng các công cụ trực quan hóa Power BI để tạo ra các biểu đồ và báo cáo dễ hiểu cho các bên liên quan.
## Dữ liệu sử dụng
https://www.kaggle.com/code/thomaskonstantin/bank-churn-data-exploration-and-churn-pred
iction/input
## Tổng quan về dữ liệu
Dữ liệu gốc được lấy từ trang wed Kangle.com dưới dạng tệp csv. Dữ liệu bao gồm 23 cột:
- Clientnum: mã số khách hàng mang tính duy nhất.
- Attrition_Flag: sự kiện nội bộ về hoạt động của khách hàng.
- Customer_Age: tuổi của khách hàng tính theo năm hiện tại.
- Gender: giới tính của khách hàng.
- Dependent_count: số người phụ thuộc.
- Education_Level: trình độ học vấn.
- Marital_Status: tình trạng hôn nhân.
- Income_Category: mức thu nhập.
- Card_Category: loại thẻ (xanh lam, bạc, vàng, bạch kim).
- Months_on_book: thời gian quan hệ tại ngân hàng.
- Total_Relationship_Count: tổng số sản phẩm khách hàng nắm giữ.
- Months_Inactive_12_mon: số tháng không hoạt động trong 12 tháng vừa qua.
- Contacts_Count_12_mon: số tháng hoạt động trong 12 tháng vừa qua.
- Credit_Limit: hạn mức thẻ tín dụng của khách hàng.
- Total_Revolving_Bal: tổng số dư nợ quay vòng trên thẻ tín dụng.
- Avg_Open_To_Buy: hạn mức tín dụng còn lại để sử dụng (trung bình 12 tháng qua).
- Total_Amt_Chng_Q4_Q1: thay đổi về số tiền giao dịch (Quý 4 so với Quý 1).
- Total_Trans_Amt: tổng số tiền giao dịch trong 12 tháng vừa qua.
- Total_Trans_Ct: tổng số giao dịch trong 12 tháng vừa qua.
- Total_Ct_Chng_Q4_Q1: Thay đổi trong số lượng giao dịch (Quý 4 so với Quý 1).
- Avg_ Utilization_Ratio: tỉ lệ sử dụng thẻ trung bình.
- Naive_Bayes_Classifier_Attrition_Flag_Card_Category_Contacts_Count_12_mon_Depend
ent_count_Education_Level_Months_Inactive_12_mon_1: Naive Bayes.
- Naive_Bayes_Classifier_Attrition_Flag_Card_Category_Contacts_Count_12_mon_Depend
ent_count_Education_Level_Months_Inactive_12_mon12: Naive Bayes.
# Làm sạch dữ liệu


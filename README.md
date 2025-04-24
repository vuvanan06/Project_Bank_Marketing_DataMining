## Phân tích Hiệu quả Chiến dịch Marketing
### Mô tả dự án
Dự án tập trung phân tích dữ liệu chiến dịch marketing của ngân hàng để xác định yếu tố ảnh hưởng đến tỷ lệ thành công và từ đó đề xuất chiến lược tối ưu.
**MÔ TẢ TẬP DỮ LIỆU:**
Tập dữ liệu bao gồm 45211 bản ghi tương ứng với 45211 khách hàng lưu trữ thông tin về chiến dịch marketing mở sổ tiết kiệm có kỳ hạn. Mỗi một bản ghi tương ứng với một khách hàng mà ngân hàng đã liên lạc để tiếp thị dịch vụ, bao gồm 10 thông tin như sau:
* **Phần A.Dữ liệu khách hàng:**
1. age: Tuổi của khách hàng (int)
2. job: Nghề nghiệp ("admin.","unknown","unemployed","management","housemaid","entrepreneur","student", "blue-collar","self-employed","retired","technician","services")
3. marital: Tình trạng hôn nhân ("married","divorced","single")
4. education: Trình độ học vấn ("unknown","secondary","primary","tertiary")
5. balance: Số dữ trong tài khoản(đơn vị: Euro)
6. loan: Hiện có vay liên tiêu dùng cá nhân nào hay không (yes/no)

* **Phần B.Thông tin liên quan tới chiến dịch tiếp thị:**
7. contact: loại kết nối liên lạc tới khách hàng ("other","telephone","cellular")
8. month: Tháng liên lạc marketing cuối cùng trong năm (jan, feb, mar...nov,dec)
9. campaign: Số lần liên lạc với khách hàng này trong một chiến dịch
10. deposit: Kết quả của đợt marketing này là khách hàng có đăng ký tiền gửi tiết kiệm hay không (yes/no)


### Công việc thực hiện:
Thu thập và làm sạch dữ liệu.

Phân tích ảnh hưởng của số lần liên lạc và thời gian tiếp thị đến tỷ lệ thành công.

Trực quan hóa dữ liệu bằng biểu đồ và bảng phân tích.

Đề xuất kế hoạch cải thiện hiệu quả chiến dịch dựa trên phân tích dữ liệu.

Sử dụng Jupyter Notebook và thư viện Pandas, NumPy để xử lý và phân tích dữ liệu.

### Kết quả đạt được:
Xác định mô hình hiệu quả nhất cho các chiến dịch marketing.

Đề xuất thời gian và số lần liên hệ tối ưu để nâng cao tỷ lệ chuyển đổi khách hàng.

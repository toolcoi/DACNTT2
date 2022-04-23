"Điều Khiển Thiết Bị Bằng Trợ Lý Ảo Google"

1. Giới Thiệu
	Đề tài sử dụng chức năng giọng nói của Google Assistant để điều khiển các thiết bị trong gia đình 
     thông qua module ESP8266,  người dùng chỉ cần nói "Ok Google" và câu lệnh "On/off" là có thể điều khiển 
     bật/tắt đèn quạt. Các thiết bị được kết nối với nhau qua mạng wifi hoặc dữ liệu di động.
2. Hướng Dẫn Sử Dụng
	Bước 1: Cấp nguồn ESP8266, nguồn điện 3V
	Bước 2: Các thiết bị như đèn, quạt được kết nối với ESP8266 thông qua cổng Digital.
	Bước 4: Cấp nguồn điện cho các thiết bị điện.
	Bước 5: Sử dụng smartphone truy cập Google Assistant
		Ok Google
		Turn on fan   // Mở quạt
		Turn off fan  // Tắt quạt
		Turn on LED   // Mở đèn
		Turn off LED  // Tắt đèn
### Lưu Ý #### 
	Module wifi ESP8266 phải đảm bảo kết nối được tới mạng wifi của gia đình.
	Smartphone có thể sử dụng cùng hoặc khác mạng wifi với module ESP8266 vẫn điều khiển được các thiết bị.

## Mã Code ###
	char auth[] = "Mã authtoken";
	char ssid[] = "Tên mạng wifi";
	char pass[] = "Mật khẩu của mạng wifi";

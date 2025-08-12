# HƯỚNG DẪN SỬ DỤNG PHẦN MỀM iAUTO

## Giới thiệu
iAUTO là một phần mềm bot tự động hỗ trợ chơi game online, được thiết kế để tự động hóa các tác vụ trong game như di chuyển, tấn công, thu thập vật phẩm, và nhiều chức năng khác.

## Yêu cầu hệ thống
- Hệ điều hành: Windows 10/11
- Quyền: Chạy với quyền Administrator
- RAM: Tối thiểu 4GB
- .NET Framework 4.7.2 trở lên

## Cài đặt và khởi động

### Bước 1: Cài đặt
1. Giải nén file iAuto.zip vào thư mục mong muốn
2. Đảm bảo tất cả file DLL và tài nguyên được giải nén đầy đủ

### Bước 2: Khởi động
1. Chuột phải vào file `iAuto.exe`
2. Chọn "Run as administrator" (Chạy với quyền quản trị)
3. Nếu có thông báo UAC, chọn "Yes"

## Giao diện chính

### Menu chính
- **File**: Quản lý cấu hình, xuất/nhập settings
- **Tools**: Các công cụ hỗ trợ
- **Help**: Hướng dẫn và thông tin

### Các tab chức năng chính

#### 1. Tab Auto (Tự động)
- **Auto Attack**: Tự động tấn công
- **Auto Move**: Tự động di chuyển
- **Auto Pick**: Tự động nhặt vật phẩm
- **Auto Buff**: Tự động buff kỹ năng
- **Auto Sell**: Tự động bán vật phẩm

#### 2. Tab Game (Game)
- **Game Path**: Đường dẫn đến game
- **Process Name**: Tên process của game
- **Hook Game**: Kết nối với game

#### 3. Tab Settings (Cài đặt)
- **Delay**: Độ trễ giữa các thao tác
- **Refresh Rate**: Tần suất cập nhật
- **Exit Conditions**: Điều kiện thoát game

## Cấu hình cơ bản

### Thiết lập game
1. Vào tab **Game**
2. Nhập đường dẫn đến file game chính
3. Nhập tên process của game (thường là "game")
4. Nhấn "Hook Game" để kết nối

### Cài đặt tự động
1. Vào tab **Auto**
2. Bật các chức năng cần thiết:
   - Auto Attack: Tự động tấn công
   - Auto Move: Tự động di chuyển
   - Auto Pick: Tự động nhặt đồ
   - Auto Buff: Tự động buff

### Cài đặt nâng cao
1. Vào tab **Settings**
2. Điều chỉnh các thông số:
   - Delay: 250ms (mặc định)
   - Refresh Rate: 2000ms
   - Exit Idle Time: 6 phút
   - Exit Offline Time: 10 phút

## Các chức năng chính

### 1. Tự động tấn công
- **Attack Key**: Phím tấn công (mặc định F1)
- **Attack List**: Danh sách mục tiêu tấn công
- **Black List**: Danh sách đen (không tấn công)

### 2. Tự động di chuyển
- **Follow Key**: Phím theo dõi
- **Move to Position**: Di chuyển đến vị trí cụ thể
- **Auto Path**: Tự động tìm đường

### 3. Tự động thu thập
- **Collect Items**: Thu thập vật phẩm
- **Drop Items**: Vứt bỏ vật phẩm không cần
- **Bank Items**: Gửi vật phẩm vào ngân hàng

### 4. Tự động buff
- **Buff HP**: Buff máu khi HP thấp
- **Buff MP**: Buff mana khi MP thấp
- **Buff Pet**: Buff thú cưng
- **Buff Skills**: Buff các kỹ năng khác

### 5. Quản lý nhiệm vụ
- **Auto Quest**: Tự động làm nhiệm vụ
- **Quest Frame**: Khung nhiệm vụ
- **Mission Types**: Các loại nhiệm vụ

## Cài đặt nâng cao

### Hotkey (Phím tắt)
- **F1**: Tấn công
- **F2**: Theo dõi
- **F3**: Thu thập
- **F4**: Buff
- **F5**: Dừng tất cả

### Cài đặt bảo mật
- **Bypass Captcha**: Bỏ qua captcha
- **Fake MAC**: Giả mạo địa chỉ MAC
- **Hide Game**: Ẩn game

### Cài đặt hiệu suất
- **Trim CPU**: Tối ưu CPU
- **Refresh Rate**: Tần suất cập nhật
- **Memory Management**: Quản lý bộ nhớ

## Xử lý sự cố

### Lỗi thường gặp

#### 1. Không thể kết nối game
- Kiểm tra game đã chạy chưa
- Kiểm tra tên process có đúng không
- Chạy với quyền Administrator

#### 2. Bot không hoạt động
- Kiểm tra các chức năng đã bật chưa
- Kiểm tra cài đặt delay
- Kiểm tra kết nối với game

#### 3. Lỗi quyền truy cập
- Chạy với quyền Administrator
- Kiểm tra antivirus có chặn không
- Kiểm tra Windows Defender

### Khắc phục sự cố
1. **Restart Bot**: Khởi động lại phần mềm
2. **Rehook Game**: Kết nối lại với game
3. **Reset Settings**: Đặt lại cài đặt mặc định
4. **Check Logs**: Kiểm tra nhật ký lỗi

## Lưu ý quan trọng

### Bảo mật
- Không chia sẻ thông tin tài khoản
- Sử dụng bot một cách thông minh
- Tránh sử dụng quá mức để tránh bị phát hiện

### Hiệu suất
- Điều chỉnh delay phù hợp với máy tính
- Không bật quá nhiều chức năng cùng lúc
- Theo dõi sử dụng CPU và RAM

### Cập nhật
- Thường xuyên kiểm tra phiên bản mới
- Cập nhật khi game có thay đổi
- Sao lưu cài đặt trước khi cập nhật

## Hỗ trợ kỹ thuật

### Thông tin liên hệ
- **Email**: [Email hỗ trợ]
- **Website**: [Website chính thức]
- **Forum**: [Diễn đàn cộng đồng]

### Tài liệu bổ sung
- **Video hướng dẫn**: [Link video]
- **FAQ**: [Câu hỏi thường gặp]
- **Wiki**: [Bách khoa toàn thư]

## Kết luận
iAUTO là một công cụ mạnh mẽ giúp tự động hóa game, nhưng cần sử dụng một cách có trách nhiệm. Hãy đọc kỹ hướng dẫn này và thực hành để sử dụng hiệu quả nhất.

---
*Lưu ý: Hướng dẫn này dựa trên phiên bản hiện tại của iAUTO. Các tính năng có thể thay đổi trong các phiên bản tương lai.*

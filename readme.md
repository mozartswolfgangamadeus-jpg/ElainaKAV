# ElainaKAV - Khan Academy Enhancement Tool

![ElainaKAV Logo](https://i.imgur.com/JDt99XK.jpeg)

**ElainaKAV** là công cụ hỗ trợ học tập mạnh mẽ dành cho Khan Academy, được phát triển bởi NguyenManhHieu. Script này cung cấp nhiều tính năng tự động hóa và tối ưu hóa trải nghiệm học tập của bạn.

## 🚀 Tính năng chính

### 🚀 Auto Farm All **[ĐANG LỖI]**
- ⚠️ **Tính năng tạm thời gặp lỗi, đang khắc phục**
- Tự động hoàn thành tất cả bài tập trong chủ đề
- Thuật toán thông minh phát hiện và xử lý exercises
- Hệ thống navigation không làm mất script
- Tùy chỉnh độ trễ giữa các bài tập (1-5 giây)

### ⏰ Auto Farm Minutes **[ĐANG LỖI]**
- ⚠️ **Tính năng tạm thời gặp lỗi, đang khắc phục**
- Tự động tích lũy phút học một cách hiệu quả
- Duy trì streak học tập hàng ngày
- Tùy chỉnh độ trễ (1-3 giây)
- Hỗ trợ multiple exercises cycling

### 📝 Question Spoof
- Thay thế câu hỏi phức tạp bằng câu hỏi đơn giản
- Đáp án luôn đúng 100%
- Thông báo động lực ngẫu nhiên
- Bypass hoàn toàn logic câu hỏi gốc

### 🎥 Video Spoof
- Tự động đánh dấu video đã xem hoàn thành
- Không cần xem hết video
- Tiết kiệm thời gian học tập đáng kể

### 🎯 Auto Answer
- Tự động trả lời câu hỏi với độ chính xác cao
- Tùy chỉnh độ trễ trả lời (1-3 giây)
- Hỗ trợ chế độ lặp lại câu hỏi
- Tự động chuyển câu hỏi tiếp theo

### 💡 Answer Revealer
- Hiển thị đáp án đúng trước khi trả lời
- Đánh dấu đáp án đúng bằng ✅
- Hỗ trợ học tập hiệu quả hơn

### ⏱️ Minute Farmer
- Bỏ qua giới hạn thời gian học tập
- Chặn termination events
- Tích lũy phút học không giới hạn

### 🎨 Tùy chỉnh giao diện
- **Custom Banner**: Thay đổi banner chào mừng
- **RGB Logo**: Logo Khan Academy với hiệu ứng màu sắc
- **Dark Mode**: Chế độ tối chuyên nghiệp
- **Custom Username & Avatar**: Thay đổi tên và ảnh đại diện

### 🐱 Bonus Features
- **onekoJs**: Thú cưng desktop cute
- **Real-time Stats**: FPS, ping, thời gian thực
- **Watermark Menu**: Giao diện điều khiển tiện lợi

## 📦 Cài đặt

### Yêu cầu
- Trình duyệt Chrome, Firefox, Edge hoặc Safari
- Extension **Tampermonkey** hoặc **Greasemonkey**

### Hướng dẫn cài đặt
1. **Cài đặt Tampermonkey**:
   - [Chrome Web Store](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
   - [Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)

2. **Install HieuKAV**:
   - Click vào link: [**INSTALL HIEUKAV**](https://github.com/Nguoibianhz/HieuKAV/raw/refs/heads/main/HieuKAV.user.js)
   - Tampermonkey sẽ mở tab cài đặt
   - Click "Install" để hoàn thành

3. **Sử dụng**:
   - Truy cập [Khan Academy](https://khanacademy.org)
   - Nhấn nút "🚀 START HIEUKAV" ở góc phải màn hình
   - Tận hưởng các tính năng!

## 🎮 Hướng dẫn sử dụng

### Giao diện chính
- **Watermark (HK)**: Hover để mở menu cài đặt
- **Status Panel**: Hiển thị FPS, ping, thời gian, trạng thái farming
- **Toast Notifications**: Thông báo trạng thái các tính năng

### Cài đặt tính năng
1. **Hover** vào watermark "HK" ở góc màn hình
2. **Check/Uncheck** các tính năng muốn sử dụng:
   - Question Spoof ✅ (Recommended)
   - Video Spoof ✅ (Recommended) 
   - Auto Answer (Tự động trả lời) ✅
   - Show Answers (Hiện đáp án) ✅
   - Minute Farmer (Bỏ qua giới hạn thời gian) ✅
   - Custom Banner, RGB Logo, Dark Mode ✅
   - ~~Auto Farm All~~ (Đang lỗi)
   - ~~Auto Farm Minutes~~ (Đang lỗi)

### Các tính năng hoạt động bình thường
- **Question Spoof + Auto Answer**: Combo mạnh nhất để hoàn thành exercises
- **Video Spoof**: Tự động hoàn thành video lessons
- **Answer Revealer**: Hiện đáp án để học hiệu quả hơn
- **Minute Farmer**: Bypass time restrictions

## ⚙️ Cấu hình nâng cao

```javascript
// Tùy chỉnh độ trễ cho các tính năng hoạt động
window.featureConfigs = {
    autoAnswerDelay: 3,        // 1-3 giây (Question Spoof + Auto Answer)
    customUsername: "Your Name",
    customPfp: "Image URL"
}
```

## 🔧 Troubleshooting

### Script không hoạt động
- Đảm bảo Tampermonkey đã bật
- Refresh lại trang Khan Academy
- Kiểm tra Console (F12) để xem lỗi

### Tính năng không hoạt động
- **Question Spoof**: Thử refresh page và bật lại
- **Video Spoof**: Đảm bảo đang ở trang video lesson
- **Auto Answer**: Cần bật Question Spoof trước

### Tính năng bị lỗi
- **Auto Farm All & Auto Farm Minutes**: Đang được khắc phục, tạm thời không sử dụng được

## 🛡️ An toàn và Bảo mật

- Script chỉ hoạt động trên Khan Academy
- Không thu thập dữ liệu cá nhân
- Không gửi thông tin ra server bên ngoài
- Code được obfuscate một phần để bảo vệ

## 📈 Phiên bản

**Current Version**: Best Hack Kav
- ✅ Question Spoof working perfectly
- ✅ Video Spoof working perfectly
- ✅ Auto Answer working perfectly
- ✅ Answer Revealer working perfectly
- ✅ Minute Farmer working perfectly
- ✅ All UI customizations working
- ⚠️ Auto Farm All - temporarily broken
- ⚠️ Auto Farm Minutes - temporarily broken

## 🔄 Updates

Script tự động cập nhật qua Tampermonkey. Các bản cập nhật sẽ sớm khắc phục:
- Auto Farm All navigation issues
- Auto Farm Minutes stability problems
- Enhanced error handling
- Performance optimizations

## 🤝 Đóng góp

Nếu bạn gặp bug hoặc có ý tưởng tính năng mới:
1. Tạo issue trên GitHub repository
2. Liên hệ qua website: [nguyenmanhhieu.info.vn](https://nguyenmanhhieu.info.vn)
3. Share feedback qua Discord/Telegram

## ⚖️ Disclaimer

- Tool này được tạo ra cho mục đích giáo dục và nghiên cứu
- Sử dụng có trách nhiệm và tuân thủ Terms of Service của Khan Academy
- Tác giả không chịu trách nhiệm cho việc sử dụng sai mục đích
- Khuyến khích sử dụng để hỗ trợ học tập chứ không thay thế việc học

#Cảm ơn HieuKAV Rất nhiều=)))))#

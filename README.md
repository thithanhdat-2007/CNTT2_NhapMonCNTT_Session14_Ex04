# Bài tập Session 14 - Ex04: So sánh ứng dụng chat cá nhân và Enterprise Workspace

Họ và tên: Thi Thành Đạt  
MSSV: N26DTCN041  
Lớp: CNTT2  
Email: thithanhdat111@gmail.com

## 1. Tình huống

Nhóm startup đang trao đổi công việc trên Zalo. Một thông báo hạn nộp bài lúc 23:59 bị khoảng 50 tin nhắn meme và tán gẫu đẩy lên phía trên. Thành viên vào nhóm muộn có thể bỏ sót thông báo, phải hỏi lại người khác hoặc tìm lại giữa nhiều tin nhắn. Vấn đề chính là nhóm đang dùng chung một luồng trò chuyện cho cả thông báo, thảo luận và nội dung ngoài công việc.

## 2. Bảng so sánh

| Tiêu chí | App chat cá nhân (ví dụ: nhóm Zalo) | Enterprise Workspace (ví dụ: Lark, Slack) |
|---|---|---|
| 1. Phân loại nội dung | Có thể tạo nhóm và ghim tin quan trọng, nhưng nếu mọi người dồn tất cả vào một nhóm thì nội dung vẫn dễ lẫn nhau. | Có thể tách không gian trao đổi theo chủ đề, dự án hoặc nhóm phụ trách; Slack dùng channel, còn Lark có nhóm chat và các bộ lọc hội thoại. |
| 2. Thảo luận theo từng việc | Các câu trả lời liên tiếp trong cùng nhóm dễ chen vào chủ đề khác nếu không có quy ước rõ ràng. | Có thể gom phản hồi theo cuộc thảo luận hoặc chủ đề phù hợp, nhất là thread trong Slack, để cuộc trò chuyện chính gọn hơn. |
| 3. Tìm lại tin nhắn và file cũ | Zalo vẫn có mục xem file, ảnh, liên kết và tin đã ghim; người dùng phải nhớ đúng nhóm hoặc từ khóa để tìm nhanh. | Có công cụ tìm kiếm trong không gian làm việc. Slack có bộ lọc tin nhắn, file, người và channel; Lark có thể tìm tin nhắn, tài liệu và nội dung khác. |
| 4. Quản lý công việc | Có nhắc hẹn và ghim tin, nhưng nếu chỉ nhắn “nhớ nộp bài” thì chưa thể hiện rõ ai phụ trách và đã hoàn thành hay chưa. | Có thể gắn nội dung trao đổi với công việc. Lark cho phép chuyển tin nhắn thành task; Slack có các công cụ quản lý việc và kết nối ứng dụng khác. |
| 5. Chi phí và mức độ làm quen | Nhóm đã quen dùng Zalo nên bắt đầu nhanh, ít phải đổi thói quen. | Cần thời gian tạo cấu trúc, hướng dẫn thành viên và có thể phát sinh chi phí theo gói hoặc công cụ được dùng. Bù lại, thông tin công việc dễ được sắp xếp hơn nếu nhóm sử dụng đúng cách. |

## 3. Đánh giá và đề xuất

Theo em, không thể khẳng định “100% công ty IT chọn Lark/Slack” vì đề bài không cung cấp khảo sát để chứng minh. Cũng không có số liệu cho thấy mọi công ty đều tiết kiệm “hàng trăm giờ họp”. Tuy vậy, với nhóm có nhiều dự án và nhiều tin nhắn mỗi ngày, công cụ doanh nghiệp có thể giúp giảm thời gian hỏi lại, tìm file và họp chỉ để nhắc lại thông tin đã gửi.

Sự đánh đổi là nhóm phải chuyển thói quen làm việc. Nếu tạo quá nhiều channel hoặc nhóm chat, thông tin lại bị chia nhỏ và khó tìm. Một số tính năng có thể phụ thuộc vào gói dịch vụ. Vì vậy, em đề xuất thử Lark cho startup trong tình huống này: nhóm có thể dùng chat, tìm kiếm tài liệu và chuyển thông báo thành công việc trong cùng một không gian. Slack cũng phù hợp nếu nhóm đã quen dùng các ứng dụng quản lý công việc khác và muốn kết nối chúng.

Để giải quyết hiện tượng “tin nhắn bị phẳng một hàng”, em đề xuất làm như sau:

1. Tạo nơi riêng cho thông báo quan trọng và nơi riêng cho trao đổi thường ngày. Không gửi meme vào nơi thông báo.
2. Đăng hạn nộp bài với tiêu đề rõ ràng, ví dụ: **[HẠN NỘP] Bài tập - 23:59 hôm nay**. Ghi thêm người phụ trách và đường dẫn đến file cần nộp.
3. Ghim thông báo quan trọng. Các câu hỏi và trả lời về cùng một việc nên nằm trong cùng cuộc thảo luận (thread nếu công cụ hỗ trợ), tránh gửi nhiều tin rời vào luồng chính.
4. Chuyển thông báo thành công việc có người nhận, hạn hoàn thành và trạng thái. Trước hạn nộp, người phụ trách kiểm tra trạng thái thay vì tổ chức họp chỉ để hỏi ai đã làm xong.
5. Sau một thời gian dùng thử, kiểm tra xem thành viên có tìm được thông báo và file cũ nhanh hơn không. Nếu cách tổ chức chưa hợp lý thì điều chỉnh số nhóm, tên nhóm và quy ước đăng tin.

Nếu chưa chuyển ngay, nhóm vẫn nên ghim thông báo trên Zalo và dùng nhắc hẹn. Đây là cách xử lý trước mắt, nhưng khi lượng thông tin công việc tăng lên, việc tách chủ đề và theo dõi task trong Enterprise Workspace sẽ thuận tiện hơn.

## 4. Kết luận

Trong tình huống của đề bài, em chọn chuyển dần sang Lark. Lợi ích chính là tách nội dung theo mục đích, tìm lại thông tin và theo dõi người phụ trách từng việc. Tuy nhiên, công cụ chỉ phát huy hiệu quả khi cả nhóm thống nhất cách đăng thông báo, thảo luận và cập nhật công việc.



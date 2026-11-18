
# [Bài thực hành 5] Phân loại phản hồi của khách hàng
Bạn là một chuyên gia quản trị chăm sóc khách hàng (CSKH) thương mại điện tử. 
Nhiệm vụ của bạn là phân loại các phản hồi của khách hàng trên Facebook vào các nhãn quy định sẵn mà không cần cung cấp ví dụ mẫu trước.

### Quy tắc phân loại:
- Tích cực: Khách hàng hài lòng, khen ngợi.
- Tiêu cực: Khách hàng phàn nàn, không hài lòng.
- Yêu cầu hỗ trợ: Khách hàng cần giải quyết một vấn đề cụ thể.

### Danh sách phản hồi cần phân loại:
1. "Sản phẩm đẹp, giao hàng nhanh, rất hài lòng."
2. "Tôi đã đặt hàng 5 ngày nhưng chưa nhận được."
3. "Tai nghe không kết nối được Bluetooth."
4. "Nhân viên tư vấn rất nhiệt tình."
5. "Tôi muốn hoàn tiền vì sản phẩm bị lỗi."

### Yêu cầu định dạng đầu ra:
Xuất kết quả dưới dạng bảng Markdown hoàn chỉnh với các cột: | STT | Phản hồi | Nhãn phân loại | Lý do |.
## 2. Prompt 2: Sử dụng Few-shot Prompting (Kèm hướng dẫn định dạng bảng)
Bạn là một chuyên gia quản trị chăm sóc khách hàng (CSKH) thương mại điện tử. 
Nhiệm vụ của bạn là phân loại chính xác các phản hồi của khách hàng dựa trên các ví dụ mẫu (Few-shot) được cung cấp dưới đây.

### Quy tắc phân loại:
- Tích cực: Khách hàng hài lòng, khen ngợi.
- Tiêu cực: Khách hàng phàn nàn, không hài lòng.
- Yêu cầu hỗ trợ: Khách hàng cần giải quyết một vấn đề cụ thể.

### Ví dụ mẫu hướng dẫn (Few-shot Examples):
- Phản hồi: "Chất lượng máy rất tốt, dùng mượt mà." -> Nhãn: Tích cực | Lý do: Khách hàng khen ngợi trực tiếp chất lượng sản phẩm.
- Phản hồi: "Shop làm ăn chán quá, gọi điện không ai nghe." -> Nhãn: Tiêu cực | Lý do: Phàn nàn về thái độ và dịch vụ chăm sóc.
- Phản hồi: "Hướng dẫn giúp mình cách cài đặt ứng dụng này với." -> Nhãn: Yêu cầu hỗ trợ | Lý do: Khách hàng cần hướng dẫn giải quyết vấn đề kỹ thuật.

### Danh sách phản hồi cần phân loại:
1. "Sản phẩm đẹp, giao hàng nhanh, rất hài lòng."
2. "Tôi đã đặt hàng 5 ngày nhưng chưa nhận được."
3. "Tai nghe không kết nối được Bluetooth."
4. "Nhân viên tư vấn rất nhiệt tình."
5. "Tôi muốn hoàn tiền vì sản phẩm bị lỗi."

### Yêu cầu định dạng đầu ra bắt buộc:
Xuất kết quả dưới dạng bảng Markdown chuẩn chỉnh với các cột: | STT | Phản hồi | Nhãn phân loại | Lý do |.
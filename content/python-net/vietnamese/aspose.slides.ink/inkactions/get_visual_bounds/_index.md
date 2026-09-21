---
title: get_visual_bounds method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.ink/inkactions/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Lấy giới hạn hiển thị của hình dạng được tính toán từ nội dung đã được render.

### Giá trị trả về

Một **aspose.slides.RectangleF** đại diện cho giới hạn hiển thị của hình dạng trong tọa độ slide.



```python
def get_visual_bounds(self):
    ...
```


### Ghi chú

Hình chữ nhật trả về đại diện cho các giới hạn song song trục của mọi nội dung được hình dạng tạo ra trong quá trình render trong không gian tọa độ slide.

Các giới hạn này có thể khác với các giới hạn mô hình của hình dạng ([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height)) và có thể chứa tọa độ âm nếu nội dung đã render mở rộng ra ngoài gốc slide.

Các giới hạn hiển thị tính đến các khía cạnh liên quan đến việc render như biến đổi (ví dụ, xoay), độ rộng và nối nét, bố cục và tràn văn bản, hình học SmartArt, và các hiệu ứng bố trí khác ảnh hưởng đến giao diện cuối cùng được render của hình dạng.

Các giới hạn trả về không bị cắt theo hình chữ nhật slide.



### Xem thêm
* lớp [`InkActions`](/slides/python-net/vi/aspose.slides.ink/inkactions)
* module [`aspose.slides.ink`](/slides/python-net/vi/aspose.slides.ink)
* thư viện [`Aspose.Slides`](/slides/python-net)
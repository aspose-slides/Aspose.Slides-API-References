---
title: get_visual_bounds method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.ink/ink/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Lấy giới hạn trực quan của hình dạng được tính toán từ nội dung đã render.

### Giá trị trả về

Một [`RectangleF`](/slides/python-net/vi/aspose.slides/rectanglef) đại diện cho giới hạn trực quan của hình dạng trong tọa độ slide.

```python
def get_visual_bounds(self):
    ...
```

### Ghi chú

Hình chữ nhật được trả về đại diện cho các giới hạn song song trục của tất cả nội dung
             được tạo ra bởi hình dạng trong quá trình render trong không gian tọa độ slide.
            
             Các giới hạn này có thể khác với các giới hạn mô hình của hình dạng
             ([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height))
             và có thể chứa tọa độ âm nếu nội dung đã render mở rộng
             ra ngoài gốc slide.
            
             Giới hạn trực quan tính đến các khía cạnh liên quan đến render như
             các phép biến đổi (ví dụ, xoay), độ rộng nét và nối,
             bố cục văn bản và tràn, SmartArt geometry, và các hiệu ứng bố cục khác
             có ảnh hưởng đến diện mạo cuối cùng sau khi render của hình dạng.
            
             Các giới hạn được trả về không bị cắt theo hình chữ nhật slide.

### Xem thêm
* lớp [`Ink`](/slides/python-net/vi/aspose.slides.ink/ink)
* lớp [`RectangleF`](/slides/python-net/vi/aspose.slides/rectanglef)
* module [`aspose.slides.ink`](/slides/python-net/vi/aspose.slides.ink)
* thư viện [`Aspose.Slides`](/slides/python-net)
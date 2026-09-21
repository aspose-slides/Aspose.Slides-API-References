---
title: get_visual_bounds method
second_title: Aspose.Slides cho Python thông qua .NET API Reference
description: 
type: docs
url: /vi/aspose.slides.smartart/smartartshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Lấy giới hạn trực quan của hình dạng được tính dựa trên nội dung đã vẽ.

### Trả về

Một **aspose.slides.RectangleF** đại diện cho giới hạn trực quan của hình dạng
             trong tọa độ slide.

```python
def get_visual_bounds(self):
    ...
```

### Ghi chú

Các giới hạn này có thể khác với các giới hạn mô hình của hình dạng
             ([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height))
             và có thể chứa tọa độ âm nếu nội dung đã vẽ mở rộng
             ra ngoài gốc slide.

Các giới hạn trực quan tính đến các khía cạnh liên quan đến việc vẽ như
             biến đổi (ví dụ, xoay), độ rộng nét và các góc nối,
             bố cục và tràn văn bản, hình học SmartArt, và các hiệu ứng bố cục
             ảnh hưởng đến diện mạo cuối cùng của hình dạng khi được vẽ.

Các giới hạn được trả về không bị cắt theo hình chữ nhật slide.

### Xem thêm
* lớp [`SmartArtShape`](/slides/python-net/vi/aspose.slides.smartart/smartartshape)
* mô-đun [`aspose.slides.smartart`](/slides/python-net/vi/aspose.slides.smartart)
* thư viện [`Aspose.Slides`](/slides/python-net)
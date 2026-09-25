---
title: get_visual_bounds method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/audioframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Lấy giới hạn trực quan của hình dạng được tính toán từ nội dung đã render của nó.

### Trả về

Một [`RectangleF`](/slides/python-net/vi/aspose.slides/rectanglef) biểu diễn giới hạn trực quan của hình dạng trong tọa độ slide.

```python
def get_visual_bounds(self):
    ...
```

### Ghi chú

Hình chữ nhật được trả về biểu diễn giới hạn theo trục của toàn bộ nội dung được hình dạng tạo ra trong quá trình render trong không gian tọa độ slide.

Các giới hạn này có thể khác với giới hạn mô hình của hình dạng ([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height)) và có thể chứa các tọa độ âm nếu nội dung đã render vượt ra ngoài nguyên gốc slide.

Giới hạn trực quan tính đến các khía cạnh liên quan đến render như biến đổi (ví dụ, quay), độ rộng nét và các mối nối, bố cục và tràn văn bản, hình học SmartArt, và các hiệu ứng bố trí khác ảnh hưởng đến ngoại hình cuối cùng của hình dạng sau khi render.

Các giới hạn được trả về không bị cắt theo hình chữ nhật slide.

### Xem thêm
* lớp [`AudioFrame`](/slides/python-net/vi/aspose.slides/audioframe)
* lớp [`RectangleF`](/slides/python-net/vi/aspose.slides/rectanglef)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
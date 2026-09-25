---
title: get_visual_bounds method
second_title: Aspose.Slides cho Python thông qua .NET API Reference
description: 
type: docs
url: /vi/aspose.slides/geometryshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Lấy giới hạn trực quan của hình dạng được tính từ nội dung đã render.

### Trả về

Một [`RectangleF`](/slides/python-net/vi/aspose.slides/rectanglef) đại diện cho giới hạn trực quan của hình dạng trong tọa độ slide.



```python
def get_visual_bounds(self):
    ...
```


### Ghi chú

Hình chữ nhật được trả về đại diện cho giới hạn thẳng hàng trục của tất cả nội dung do hình dạng tạo ra trong quá trình render trong không gian tọa độ slide.

Những giới hạn này có thể khác với giới hạn mô hình của hình dạng ([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height)) và có thể chứa tọa độ âm nếu nội dung đã render vượt ra ngoài gốc slide.

Giới hạn trực quan tính đến các khía cạnh liên quan đến render như các biến đổi (ví dụ, xoay), độ rộng nét và các nối, bố cục văn bản và tràn, hình học SmartArt, và các hiệu ứng bố cục khác ảnh hưởng đến diện mạo cuối cùng của hình dạng sau khi render.

Các giới hạn được trả về không bị cắt theo hình chữ nhật slide.



### Xem thêm
* lớp [`GeometryShape`](/slides/python-net/vi/aspose.slides/geometryshape)
* lớp [`RectangleF`](/slides/python-net/vi/aspose.slides/rectanglef)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
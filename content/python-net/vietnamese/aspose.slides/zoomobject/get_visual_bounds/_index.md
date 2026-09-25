---
title: get_visual_bounds method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/zoomobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Lấy giới hạn trực quan của hình dạng được tính từ nội dung đã được hiển thị.

### Trả về

Một [`RectangleF`](/slides/python-net/vi/aspose.slides/rectanglef) đại diện cho giới hạn trực quan của hình dạng trong tọa độ slide.



```python
def get_visual_bounds(self):
    ...
```


### Ghi chú

Hình chữ nhật trả về đại diện cho các giới hạn được căn trục của mọi nội dung do hình dạng tạo ra trong quá trình hiển thị trong không gian tọa độ slide.

Các giới hạn này có thể khác với các giới hạn mô hình của hình dạng ([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height)) và có thể chứa tọa độ âm nếu nội dung đã hiển thị mở rộng ra ngoài gốc slide.

Giới hạn trực quan tính đến các khía cạnh liên quan đến việc hiển thị như biến đổi (ví dụ, xoay), độ rộng nét và nối, bố cục văn bản và tràn, hình học SmartArt, và các hiệu ứng bố cục khác ảnh hưởng đến hình thức cuối cùng của hình dạng sau khi hiển thị.

Các giới hạn trả về không bị cắt theo hình chữ nhật slide.



### Xem Thêm
* lớp [`ZoomObject`](/slides/python-net/vi/aspose.slides/zoomobject)
* lớp [`RectangleF`](/slides/python-net/vi/aspose.slides/rectanglef)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
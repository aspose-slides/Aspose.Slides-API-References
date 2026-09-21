---
title: get_visual_bounds method
second_title: Aspose.Slides cho Python qua .NET API Reference
description: 
type: docs
url: /vi/aspose.slides/table/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Lấy giới hạn hình ảnh của đối tượng được tính từ nội dung đã render.

### Trả về

Một **aspose.slides.RectangleF** đại diện cho giới hạn hình ảnh của đối tượng
             trong tọa độ slide.



```python
def get_visual_bounds(self):
    ...
```


### Ghi chú

Hình chữ nhật trả về đại diện cho giới hạn được căn trục của tất cả nội dung
             được đối tượng tạo ra trong quá trình render trong không gian tọa độ slide.
            
             Những giới hạn này có thể khác với giới hạn mô hình của đối tượng
             ([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height))
             và có thể chứa tọa độ âm nếu nội dung đã render vượt ra ngoài gốc slide.
            
             Giới hạn hình ảnh tính đến các khía cạnh liên quan đến render như
             biến đổi (ví dụ, quay), độ rộng và nối của nét vẽ,
             bố cục văn bản và tràn, hình học SmartArt, và các hiệu ứng bố cục khác
             ảnh hưởng đến vẻ ngoài cuối cùng khi render đối tượng.
            
             Các giới hạn trả về không bị cắt theo hình chữ nhật slide.



### Xem thêm
* lớp [`Table`](/slides/python-net/vi/aspose.slides/table)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
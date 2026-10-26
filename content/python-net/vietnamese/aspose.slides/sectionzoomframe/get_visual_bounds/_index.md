---
title: get_visual_bounds method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/sectionzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Lấy giới hạn trực quan của hình dạng được tính từ nội dung đã render.

### Trả về

Một [`RectangleF`](/slides/python-net/vi/aspose.slides/rectanglef) đại diện cho giới hạn trực quan của hình dạng
             trong tọa độ slide.



```python
def get_visual_bounds(self):
    ...
```


### Ghi chú

Hình chữ nhật trả về đại diện cho giới hạn song song với trục của tất cả nội dung
             được tạo ra bởi hình dạng trong quá trình render trong không gian tọa độ slide.
            
             Các giới hạn này có thể khác với giới hạn mô hình của hình dạng
             ([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height))
             và có thể chứa tọa độ âm nếu nội dung đã render vượt ra ngoài gốc slide.
            
             Giới hạn trực quan tính đến các khía cạnh liên quan đến render như
             biến đổi (ví dụ, quay), độ rộng nét và các mối nối,
             bố cục và tràn văn bản, hình học SmartArt, và các hiệu ứng bố trí khác
             ảnh hưởng đến hình dạng khi render cuối cùng.
            
             Các giới hạn trả về không bị cắt theo hình chữ nhật slide.



### Xem thêm
* lớp [`SectionZoomFrame`](/slides/python-net/vi/aspose.slides/sectionzoomframe)
* lớp [`RectangleF`](/slides/python-net/vi/aspose.slides/rectanglef)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
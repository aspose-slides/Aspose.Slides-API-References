---
title: get_visual_bounds method
second_title: Aspose.Slides cho Python qua .NET API Tham khảo
description: 
type: docs
url: /vi/aspose.slides/summaryzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Lấy giới hạn trực quan của hình dạng được tính toán từ nội dung đã render.

### Trả về

Một [`RectangleF`](/slides/python-net/vi/aspose.slides/rectanglef) đại diện cho giới hạn trực quan của hình dạng
             trong tọa độ slide.



```python
def get_visual_bounds(self):
    ...
```


### Ghi chú

Hình chữ nhật trả về đại diện cho giới hạn dọc trục của tất cả nội dung
             được hình dạng tạo ra trong quá trình render trong không gian tọa độ slide.
            
             Những giới hạn này có thể khác với giới hạn mô hình của hình dạng
             ([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height))
             và có thể chứa tọa độ âm nếu nội dung đã render vượt ra
             ngoài nguồn gốc slide.
            
             Giới hạn trực quan tính đến các khía cạnh liên quan đến render như
             biến đổi (ví dụ, quay), độ rộng nét và nối,
             bố cục văn bản và tràn, hình học SmartArt, và các hiệu ứng bố cục khác
             ảnh hưởng đến ngoại hình cuối cùng đã render của hình dạng.
            
             Các giới hạn trả về không bị cắt theo hình chữ nhật slide.



### Xem Thêm
* lớp [`SummaryZoomFrame`](/slides/python-net/vi/aspose.slides/summaryzoomframe)
* lớp [`RectangleF`](/slides/python-net/vi/aspose.slides/rectanglef)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
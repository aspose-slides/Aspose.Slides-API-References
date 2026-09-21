---
title: get_visual_bounds method
second_title: Tham chiếu API .NET của Aspose.Slides cho Python
description: 
type: docs
url: /vi/aspose.slides/legacydiagram/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Lấy giới hạn hình ảnh của hình dạng được tính toán từ nội dung đã hiển thị.

### Trả về

A **aspose.slides.RectangleF** that represents the visual bounds of the shape
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### Ghi chú

Hình chữ nhật trả về đại diện cho giới hạn dọc trục của tất cả nội dung
             được hình dạng tạo ra trong quá trình render trong không gian tọa độ slide.
            
             Các giới hạn này có thể khác với giới hạn mô hình của hình dạng
             ([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height))
             và có thể chứa tọa độ âm nếu nội dung đã render mở rộng ra ngoài gốc slide.
            
             Giới hạn hình ảnh tính đến các khía cạnh liên quan đến việc render như
             chuyển đổi (ví dụ, quay), độ rộng nét và nối,
             bố cục văn bản và tràn, hình học SmartArt, và các hiệu ứng bố cục khác
             ảnh hưởng đến sự hiển thị cuối cùng của hình dạng.
            
             Các giới hạn trả về không được cắt vào hình chữ nhật slide.



### Xem thêm
* lớp [`LegacyDiagram`](/slides/python-net/vi/aspose.slides/legacydiagram)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
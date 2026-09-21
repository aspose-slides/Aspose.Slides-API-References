---
title: get_visual_bounds method
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/chart/get_visual_bounds/
weight: 50
---
## get_visual_bounds(self) {#}
Lấy giới hạn trực quan của hình dạng được tính từ nội dung đã render.

### Giá trị trả về

Một **aspose.slides.RectangleF** đại diện cho giới hạn trực quan của hình dạng
             trong tọa độ slide.



```python
def get_visual_bounds(self):
    ...
```


### Ghi chú

Hình chữ nhật trả về đại diện cho giới hạn căn trục của toàn bộ nội dung
             được hình dạng tạo ra trong quá trình render trong không gian tọa độ slide.
            
             Các giới hạn này có thể khác với giới hạn mô hình của hình dạng
             ([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height))
             và có thể chứa các tọa độ âm nếu nội dung đã render vượt ra ngoài gốc slide.
            
             Giới hạn trực quan tính đến các khía cạnh liên quan đến render như
             các phép biến đổi (ví dụ, quay), độ rộng nét và các nối,
             bố cục và tràn văn bản, hình học SmartArt, và các hiệu ứng bố cục khác
             ảnh hưởng đến vẻ ngoài cuối cùng được render của hình dạng.
            
             Các giới hạn trả về không bị cắt theo hình chữ nhật slide.



### Xem thêm
* lớp [`Chart`](/slides/python-net/vi/aspose.slides.charts/chart)
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)
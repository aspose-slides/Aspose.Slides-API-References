---
title: get_visual_bounds method
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/chart/get_visual_bounds/
weight: 50
---
## get_visual_bounds(self) {#}
Lấy giới hạn hình ảnh của hình dạng được tính toán từ nội dung đã được kết xuất.

### Trả về

A [`RectangleF`](/slides/python-net/vi/aspose.slides/rectanglef) that represents the visual bounds of the shape
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### Ghi chú

Hình chữ nhật được trả lại đại diện cho các giới hạn song song trục của tất cả nội dung
             được hình dạng tạo ra trong quá trình kết xuất trong không gian tọa độ slide.
            
             Các giới hạn này có thể khác với các giới hạn mô hình của hình dạng
             ([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height))
             và có thể chứa các tọa độ âm nếu nội dung đã kết xuất mở rộng ra
             ngoài gốc slide.
            
             Các giới hạn hình ảnh tính đến các yếu tố liên quan đến việc kết xuất như
             các phép biến đổi (ví dụ, quay), độ rộng nét và các mối nối,
             bố cục và tràn văn bản, hình học SmartArt, và các hiệu ứng bố cục khác
             ảnh hưởng đến giao diện cuối cùng đã được kết xuất của hình dạng.
            
             Các giới hạn được trả lại không bị cắt theo hình chữ nhật slide.



### Xem thêm
* lớp [`Chart`](/slides/python-net/vi/aspose.slides.charts/chart)
* lớp [`RectangleF`](/slides/python-net/vi/aspose.slides/rectanglef)
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)
---
title: get_visual_bounds method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/zoomobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Trả về giới hạn hình ảnh của shape được tính dựa trên nội dung đã được hiển thị.

### Trả về

Một **aspose.slides.RectangleF** biểu diễn giới hạn hình ảnh của shape trong tọa độ slide.



```python
def get_visual_bounds(self):
    ...
```


### Ghi chú

Hình chữ nhật được trả về biểu diễn giới hạn thẳng hàng trục của tất cả nội dung được shape tạo ra trong quá trình hiển thị trong không gian tọa độ slide.
             
Các giới hạn này có thể khác với giới hạn mô hình của shape ([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height)) và có thể chứa tọa độ âm nếu nội dung đã hiển thị mở rộng ra ngoài gốc slide.
             
Giới hạn hình ảnh tính đến các yếu tố liên quan đến việc hiển thị như biến đổi (ví dụ, quay), độ rộng nét và các mối nối, bố trí và tràn văn bản, hình học SmartArt, và các hiệu ứng bố trí khác ảnh hưởng đến diện mạo cuối cùng của shape sau khi được hiển thị.
             
Các giới hạn được trả về không bị cắt theo hình chữ nhật slide.



### Xem thêm
* lớp [`ZoomObject`](/slides/python-net/vi/aspose.slides/zoomobject)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
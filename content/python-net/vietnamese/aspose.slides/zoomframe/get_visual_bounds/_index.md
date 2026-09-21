---
title: get_visual_bounds method
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides/zoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Lấy giới hạn trực quan của hình dạng được tính toán từ nội dung đã render.

### Trả về

Một **aspose.slides.RectangleF** biểu thị giới hạn trực quan của hình dạng trong tọa độ slide.



```python
def get_visual_bounds(self):
    ...
```


### Ghi chú

Hình chữ nhật được trả về biểu thị giới hạn thẳng hàng của toàn bộ nội dung do hình dạng tạo ra trong quá trình render trong không gian tọa độ slide.

Các giới hạn này có thể khác với giới hạn mô hình của hình dạng ([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height)) và có thể chứa tọa độ âm nếu nội dung đã render mở rộng ra ngoài gốc slide.

Giới hạn trực quan tính đến các khía cạnh liên quan đến render như các biến đổi (ví dụ, xoay), độ rộng nét và nối, bố cục và tràn văn bản, hình học SmartArt, và các hiệu ứng bố trí khác ảnh hưởng đến diện mạo cuối cùng của hình dạng khi được render.

Các giới hạn trả về không bị cắt theo hình chữ nhật slide.



### Xem thêm
* lớp [`ZoomFrame`](/slides/python-net/vi/aspose.slides/zoomframe)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
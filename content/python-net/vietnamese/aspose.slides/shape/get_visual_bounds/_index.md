---
title: get_visual_bounds method
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides/shape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Lấy giới hạn trực quan của hình dạng được tính toán từ nội dung đã render.

### Giá trị trả về

Một **aspose.slides.RectangleF** biểu thị giới hạn trực quan của hình dạng trong tọa độ slide.



```python
def get_visual_bounds(self):
    ...
```


### Ghi chú

Hình chữ nhật được trả về biểu thị giới hạn song song trục của toàn bộ nội dung do hình dạng tạo ra trong quá trình render trong không gian tọa độ slide.

Các giới hạn này có thể khác với giới hạn mô hình của hình dạng ([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height)) và có thể chứa tọa độ âm nếu nội dung đã render mở rộng ra ngoài gốc slide.

Giới hạn trực quan tính đến các khía cạnh liên quan đến render như biến đổi (ví dụ, quay), độ rộng nét và nối, bố cục và tràn văn bản, hình học SmartArt, và các hiệu ứng bố cục khác ảnh hưởng đến hình dạng khi render cuối cùng.

Các giới hạn được trả về không bị cắt theo hình chữ nhật slide.



### Xem thêm
* lớp [`Shape`](/slides/python-net/vi/aspose.slides/shape)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
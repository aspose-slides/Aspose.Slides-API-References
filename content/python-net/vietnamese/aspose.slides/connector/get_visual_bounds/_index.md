---
title: get_visual_bounds method
second_title: Aspose.Slides cho Python qua .NET API Reference
description: 
type: docs
url: /vi/aspose.slides/connector/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Lấy giới hạn trực quan của shape được tính từ nội dung đã render.

### Trả về

Một **aspose.slides.RectangleF** đại diện cho giới hạn trực quan của shape trong tọa độ slide.



```python
def get_visual_bounds(self):
    ...
```


### Ghi chú

Hình chữ nhật trả về đại diện cho các giới hạn căn trục của tất cả nội dung do shape tạo ra trong quá trình render trong không gian tọa độ slide.

Các giới hạn này có thể khác với các giới hạn mô hình của shape ([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height)) và có thể chứa tọa độ âm nếu nội dung đã render mở rộng ra ngoài gốc slide.

Giới hạn trực quan tính đến các khía cạnh liên quan đến render như biến đổi (ví dụ, quay), độ rộng nét và các mối nối, bố cục và tràn văn bản, geometry của SmartArt, và các hiệu ứng bố cục khác ảnh hưởng đến hình dạng cuối cùng khi render.

Các giới hạn trả về không bị cắt theo hình chữ nhật slide.



### Xem thêm
* lớp [`Connector`](/slides/python-net/vi/aspose.slides/connector)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
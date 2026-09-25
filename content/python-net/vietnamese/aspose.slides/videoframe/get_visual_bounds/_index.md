---
title: get_visual_bounds method
second_title: Aspose.Slides cho Python thông qua .NET API Reference
description: 
type: docs
url: /vi/aspose.slides/videoframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Lấy giới hạn trực quan của hình dạng được tính toán từ nội dung đã được hiển thị.

### Giá trị trả về

Một [`RectangleF`](/slides/python-net/vi/aspose.slides/rectanglef) đại diện cho giới hạn trực quan của hình dạng trong tọa độ slide.



```python
def get_visual_bounds(self):
    ...
```


### Ghi chú

Hình chữ nhật được trả về đại diện cho các giới hạn đã căn trục của tất cả nội dung được hình dạng tạo ra trong quá trình hiển thị trong không gian tọa độ slide.

Các giới hạn này có thể khác với các giới hạn mô hình của hình dạng ([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height)) và có thể chứa các tọa độ âm nếu nội dung đã hiển thị mở rộng ra ngoài gốc slide.

Các giới hạn trực quan tính đến các khía cạnh liên quan tới việc hiển thị như các phép biến đổi (ví dụ, quay), độ rộng nét và các điểm nối, bố cục và tràn văn bản, hình học SmartArt, và các hiệu ứng bố cục khác ảnh hưởng tới diện mạo cuối cùng của hình dạng khi được hiển thị.

Các giới hạn được trả về không bị cắt theo hình chữ nhật slide.



### Xem thêm
* lớp [`VideoFrame`](/slides/python-net/vi/aspose.slides/videoframe)
* lớp [`RectangleF`](/slides/python-net/vi/aspose.slides/rectanglef)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
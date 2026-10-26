---
title: get_visual_bounds method
second_title: Aspose.Slides cho Python qua API .NET
description: 
type: docs
url: /vi/aspose.slides/summaryzoomsection/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Lấy giới hạn hình ảnh của hình dạng được tính từ nội dung đã hiển thị của nó.

### Trả về

Một [`RectangleF`](/slides/python-net/vi/aspose.slides/rectanglef) đại diện cho giới hạn hình ảnh của hình dạng trong tọa độ slide.



```python
def get_visual_bounds(self):
    ...
```


### Ghi chú

Hình chữ nhật được trả về đại diện cho giới hạn song song với trục của tất cả nội dung
được hình dạng tạo ra trong quá trình hiển thị trong không gian tọa độ slide.

Các giới hạn này có thể khác với giới hạn mô hình của hình dạng
([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height))
và có thể chứa tọa độ âm nếu nội dung đã hiển thị mở rộng
ra ngoài gốc slide.

Giới hạn hình ảnh tính đến các khía cạnh liên quan tới việc hiển thị như
biến đổi (ví dụ, xoay), độ rộng đường viền và các nối,
bố cục văn bản và tràn, hình học SmartArt, và các hiệu ứng bố cục khác
ảnh hưởng đến vẻ ngoài cuối cùng của hình dạng sau khi hiển thị.

Các giới hạn được trả về không bị cắt ghép theo hình chữ nhật slide.



### Xem thêm
* lớp [`SummaryZoomSection`](/slides/python-net/vi/aspose.slides/summaryzoomsection)
* lớp [`RectangleF`](/slides/python-net/vi/aspose.slides/rectanglef)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
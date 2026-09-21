---
title: get_visual_bounds method
second_title: Aspose.Slides cho Python qua Tham chiếu API .NET
description: 
type: docs
url: /vi/aspose.slides/autoshape/get_visual_bounds/
weight: 70
---
## get_visual_bounds(self) {#}
Lấy giới hạn trực quan của hình dạng được tính toán từ nội dung đã render.

### Trả về

Một **aspose.slides.RectangleF** đại diện cho giới hạn trực quan của hình dạng trong tọa độ slide.



```python
def get_visual_bounds(self):
    ...
```


### Ghi chú

Đoạn hình chữ nhật trả về đại diện cho giới hạn căn trục của tất cả nội dung
được hình dạng tạo ra trong quá trình render trong không gian tọa độ slide.

Các giới hạn này có thể khác với giới hạn mô hình của hình dạng
([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height))
và có thể chứa tọa độ âm nếu nội dung đã render mở rộng
ra ngoài gốc slide.

Giới hạn trực quan tính đến các khía cạnh liên quan đến việc render như
các biến đổi (ví dụ, quay), độ rộng nét và các nối,
bố cục và tràn văn bản, hình học SmartArt, và các hiệu ứng bố cục khác
ảnh hưởng đến dạng hiển thị cuối cùng của hình dạng.

Các giới hạn trả về không bị cắt theo hình chữ nhật slide.



### Xem thêm
* lớp [`AutoShape`](/slides/python-net/vi/aspose.slides/autoshape)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
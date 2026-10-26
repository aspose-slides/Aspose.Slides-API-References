---
title: get_visual_bounds method
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/legacydiagram/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Lấy giới hạn trực quan của hình dạng được tính toán từ nội dung đã render.

### Trả về

Một [`RectangleF`](/slides/python-net/vi/aspose.slides/rectanglef) biểu thị giới hạn trực quan của hình dạng trong tọa độ slide.

```python
def get_visual_bounds(self):
    ...
```


### Ghi chú

Đoạn hình chữ nhật được trả về biểu thị các giới hạn song song trục của mọi nội dung
được tạo ra bởi hình dạng trong quá trình render trong không gian tọa độ slide.

Các giới hạn này có thể khác với các giới hạn mô hình của hình dạng
([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height))
và có thể chứa các tọa độ âm nếu nội dung được render mở rộng
ra ngoài gốc slide.

Các giới hạn trực quan tính đến các khía cạnh liên quan đến việc render như
các biến đổi (ví dụ, quay), độ rộng nét và các góc nối,
bố cục văn bản và tràn, hình học SmartArt, và các hiệu ứng bố cục khác
điều ảnh hưởng đến dạng hình cuối cùng được render của hình dạng.

Các giới hạn được trả về không bị cắt theo hình chữ nhật slide.


### Xem thêm
* lớp [`LegacyDiagram`](/slides/python-net/vi/aspose.slides/legacydiagram)
* lớp [`RectangleF`](/slides/python-net/vi/aspose.slides/rectanglef)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
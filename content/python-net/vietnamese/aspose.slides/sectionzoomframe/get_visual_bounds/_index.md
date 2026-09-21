---
title: get_visual_bounds method
second_title: Aspose.Slides cho Python qua Tham khảo API .NET
description: 
type: docs
url: /vi/aspose.slides/sectionzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Truy xuất giới hạn trực quan của hình dạng được tính toán từ nội dung đã render của nó.

### Trả về

Một **aspose.slides.RectangleF** đại diện cho giới hạn trực quan của hình dạng trong tọa độ slide.



```python
def get_visual_bounds(self):
    ...
```


### Ghi chú

Hình chữ nhật được trả về đại diện cho các giới hạn căn trục của tất cả nội dung do hình dạng tạo ra trong quá trình render trong không gian tọa độ slide.

Các giới hạn này có thể khác với giới hạn mô hình của hình dạng ([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height)) và có thể chứa tọa độ âm nếu nội dung đã render vượt ra ngoài gốc slide.

Giới hạn trực quan tính đến các khía cạnh liên quan đến render như biến đổi (ví dụ, quay), độ rộng nét và các nút nối, bố cục và tràn văn bản, hình học SmartArt, và các hiệu ứng bố trí khác ảnh hưởng đến giao diện cuối cùng đã render của hình dạng.

Các giới hạn được trả về không được cắt theo hình chữ nhật slide.



### Xem thêm
* lớp [`SectionZoomFrame`](/slides/python-net/vi/aspose.slides/sectionzoomframe)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
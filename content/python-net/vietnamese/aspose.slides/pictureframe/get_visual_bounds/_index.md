---
title: get_visual_bounds method
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/pictureframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Lấy giới hạn hình ảnh của hình được tính từ nội dung đã render của nó.

### Returns

Một [`RectangleF`](/slides/python-net/vi/aspose.slides/rectanglef) đại diện cho giới hạn hình ảnh của hình trong tọa độ slide.



```python
def get_visual_bounds(self):
    ...
```


### Remarks

Đoạn hình chữ nhật được trả về đại diện cho các giới hạn song song trục của tất cả nội dung
được hình tạo ra trong quá trình render trong không gian tọa độ slide.

Các giới hạn này có thể khác với các giới hạn mô hình của hình
([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height))
và có thể chứa tọa độ âm nếu nội dung đã render vượt quá gốc slide.

Giới hạn hình ảnh tính đến các khía cạnh liên quan tới việc render như
các biến đổi (ví dụ, quay), độ rộng nét và các nối,
bố cục văn bản và tràn, hình học SmartArt, và các hiệu ứng bố cục khác
ảnh hưởng đến diện mạo cuối cùng đã render của hình.

Các giới hạn được trả về không bị cắt theo hình chữ nhật slide.



### See Also
* lớp [`PictureFrame`](/slides/python-net/vi/aspose.slides/pictureframe)
* lớp [`RectangleF`](/slides/python-net/vi/aspose.slides/rectanglef)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
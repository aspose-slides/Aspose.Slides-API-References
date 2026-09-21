---
title: get_visual_bounds method
second_title: Aspose.Slides cho Python qua .NET Tham khảo API
description: 
type: docs
url: /vi/aspose.slides/groupshape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Lấy giới hạn trực quan của hình được tính từ nội dung đã được hiển thị.

### Trả về

Một **aspose.slides.RectangleF** đại diện cho giới hạn trực quan của hình
             trong tọa độ slide.



```python
def get_visual_bounds(self):
    ...
```


### Ghi chú

Hình chữ nhật được trả về đại diện cho các giới hạn thẳng hàng của tất cả nội dung được tạo ra bởi hình trong quá trình hiển thị trong không gian tọa độ slide.

Các giới hạn này có thể khác với các giới hạn mô hình của hình ([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height))
và có thể chứa tọa độ âm nếu nội dung đã hiển thị vượt ra ngoài gốc slide.

Giới hạn trực quan tính đến các khía cạnh liên quan đến quá trình hiển thị như biến đổi (ví dụ, quay), độ rộng nét và góc nối,
bố cục văn bản và tràn, hình học SmartArt, và các hiệu ứng bố cục khác ảnh hưởng đến hình dạng cuối cùng khi được hiển thị.

Các giới hạn được trả về không bị cắt theo hình chữ nhật slide.



### Xem thêm
* lớp [`GroupShape`](/slides/python-net/vi/aspose.slides/groupshape)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
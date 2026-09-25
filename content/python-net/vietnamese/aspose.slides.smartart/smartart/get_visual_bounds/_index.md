---
title: get_visual_bounds method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.smartart/smartart/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Lấy giới hạn trực quan của hình dựa trên nội dung đã render.

### Trả về

Một [`RectangleF`](/slides/python-net/vi/aspose.slides/rectanglef) đại diện cho giới hạn trực quan của hình
             trong tọa độ slide.



```python
def get_visual_bounds(self):
    ...
```


### Ghi chú

Hình chữ nhật được trả về đại diện cho các giới hạn theo trục của tất cả nội dung do hình tạo ra trong quá trình render trong không gian tọa độ slide.
            
             Các giới hạn này có thể khác với giới hạn mô hình của hình ([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height))
             và có thể chứa tọa độ âm nếu nội dung đã render mở rộng ra ngoài gốc slide.
            
             Giới hạn trực quan tính đến các yếu tố liên quan đến render như biến đổi (ví dụ, quay), độ rộng nét và các nối,
             cách bố trí và tràn văn bản, hình học SmartArt, và các hiệu ứng bố cục khác ảnh hưởng tới diện mạo cuối cùng của hình sau khi render.
            
             Các giới hạn được trả về không bị cắt theo hình chữ nhật slide.



### Xem thêm
* lớp [`SmartArt`](/slides/python-net/vi/aspose.slides.smartart/smartart)
* lớp [`RectangleF`](/slides/python-net/vi/aspose.slides/rectanglef)
* mô-đun [`aspose.slides.smartart`](/slides/python-net/vi/aspose.slides.smartart)
* thư viện [`Aspose.Slides`](/slides/python-net)
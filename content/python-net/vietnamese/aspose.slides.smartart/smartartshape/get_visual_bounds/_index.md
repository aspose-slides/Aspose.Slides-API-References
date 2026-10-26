---
title: get_visual_bounds method
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides.smartart/smartartshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Lấy giới hạn trực quan của hình dạng được tính toán dựa trên nội dung đã vẽ.

### Giá trị trả về

Một [`RectangleF`](/slides/python-net/vi/aspose.slides/rectanglef) đại diện cho giới hạn trực quan của hình dạng
             trong tọa độ slide.



```python
def get_visual_bounds(self):
    ...
```


### Ghi chú

Đoạn hình chữ nhật trả về đại diện cho giới hạn căn trục của toàn bộ nội dung
             do hình dạng tạo ra trong quá trình vẽ trong không gian tọa độ slide.
            
             Những giới hạn này có thể khác với giới hạn mô hình của hình dạng
             ([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height))
             và có thể chứa tọa độ âm nếu nội dung đã vẽ mở rộng
             vượt ra ngoài gốc slide.
            
             Giới hạn trực quan tính đến các khía cạnh liên quan tới việc vẽ như
             các biến đổi (ví dụ, xoay), độ rộng nét và các điểm nối,
             bố cục văn bản và tràn, hình học SmartArt, và các hiệu ứng bố cục khác
             ảnh hưởng đến diện mạo cuối cùng của hình dạng khi được vẽ.
            
             Các giới hạn trả về không bị cắt theo hình chữ nhật slide.



### Xem thêm
* lớp [`SmartArtShape`](/slides/python-net/vi/aspose.slides.smartart/smartartshape)
* lớp [`RectangleF`](/slides/python-net/vi/aspose.slides/rectanglef)
* module [`aspose.slides.smartart`](/slides/python-net/vi/aspose.slides.smartart)
* thư viện [`Aspose.Slides`](/slides/python-net)
---
title: get_visual_bounds method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/pictureframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Lấy giới hạn trực quan của hình dạng được tính toán từ nội dung đã hiển thị của nó.

### Trả về

Một **aspose.slides.RectangleF** đại diện cho giới hạn trực quan của hình dạng
             trong tọa độ slide.



```python
def get_visual_bounds(self):
    ...
```


### Ghi chú

Đo hình chữ nhật được trả về đại diện cho các giới hạn căn trục của tất cả nội dung
             được hình tạo ra trong quá trình hiển thị trong không gian tọa độ slide.
            
             Các giới hạn này có thể khác với các giới hạn mô hình của hình dạng
             ([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height))
             và có thể chứa tọa độ âm nếu nội dung đã hiển thị mở rộng
             ra ngoài gốc slide.
            
             Các giới hạn trực quan cân nhắc các khía cạnh liên quan đến việc hiển thị như
             biến đổi (ví dụ, rotation), độ rộng nét và các khớp,
             bố cục và tràn văn bản, SmartArt geometry, và các hiệu ứng bố cục khác
             ảnh hưởng đến giao diện cuối cùng của hình sau khi được hiển thị.
            
             Các giới hạn được trả về không bị cắt giảm theo hình chữ nhật slide.



### Xem thêm
* lớp [`PictureFrame`](/slides/python-net/vi/aspose.slides/pictureframe)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
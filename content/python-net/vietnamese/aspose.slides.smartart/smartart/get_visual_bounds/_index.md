---
title: get_visual_bounds method
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides.smartart/smartart/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Lấy giới hạn hình ảnh của hình dạng được tính toán từ nội dung đã được kết xuất.

### Returns

Một **aspose.slides.RectangleF** biểu thị giới hạn hình ảnh của hình dạng
             trong tọa độ slide.



```python
def get_visual_bounds(self):
    ...
```


### Remarks

Hình chữ nhật được trả về biểu thị giới hạn căn trục của tất cả nội dung
             được hình dạng tạo ra trong quá trình kết xuất trong không gian tọa độ slide.
            
             Các giới hạn này có thể khác với giới hạn mô hình của hình dạng
             ([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height))
             và có thể chứa tọa độ âm nếu nội dung được kết xuất mở rộng ra ngoài gốc slide.
            
             Giới hạn hình ảnh tính đến các khía cạnh liên quan đến việc kết xuất như
             chuyển đổi (ví dụ, quay), độ rộng nét và mối nối,
             bố cục văn bản và tràn, hình học SmartArt, và các hiệu ứng bố cục khác ảnh hưởng đến diện mạo cuối cùng của hình dạng sau khi kết xuất.
            
             Các giới hạn trả về không bị cắt theo hình chữ nhật slide.



### See Also
* lớp [`SmartArt`](/slides/python-net/vi/aspose.slides.smartart/smartart)
* mô-đun [`aspose.slides.smartart`](/slides/python-net/vi/aspose.slides.smartart)
* thư viện [`Aspose.Slides`](/slides/python-net)
---
title: get_visual_bounds method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.ink/ink/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Lấy giới hạn trực quan của hình dạng được tính từ nội dung đã được vẽ.

### Trả về

Một **aspose.slides.RectangleF** đại diện cho giới hạn trực quan của hình dạng
             trong tọa độ slide.



```python
def get_visual_bounds(self):
    ...
```


### Ghi chú

Hình chữ nhật được trả về đại diện cho các giới hạn song song trục của mọi nội dung được hình dạng tạo ra trong quá trình vẽ trong không gian tọa độ slide.
            
Các giới hạn này có thể khác với các giới hạn mô hình của hình dạng ([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height))
và có thể chứa tọa độ âm nếu nội dung đã vẽ mở rộng vượt quá gốc slide.
            
Các giới hạn trực quan tính đến các khía cạnh liên quan tới việc vẽ như biến đổi (ví dụ, xoay), độ rộng và nối nét, bố cục và tràn văn bản, hình học SmartArt, và các hiệu ứng bố cục khác ảnh hưởng đến hình dạng khi được vẽ cuối cùng.
            
Các giới hạn được trả về không bị cắt theo hình chữ nhật slide.



### Xem thêm
* lớp [`Ink`](/slides/python-net/vi/aspose.slides.ink/ink)
* mô-đun [`aspose.slides.ink`](/slides/python-net/vi/aspose.slides.ink)
* thư viện [`Aspose.Slides`](/slides/python-net)
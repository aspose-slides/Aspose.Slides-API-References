---
title: get_visual_bounds method
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides/summaryzoomsection/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Lấy giới hạn trực quan của hình được tính từ nội dung đã render.

### Returns

Một **aspose.slides.RectangleF** đại diện cho giới hạn trực quan của hình
             trong tọa độ slide.



```python
def get_visual_bounds(self):
    ...
```


### Remarks

Hình chữ nhật được trả về đại diện cho các giới hạn song song với trục của toàn bộ nội dung do hình tạo ra trong quá trình render trong không gian tọa độ slide.
            
Các giới hạn này có thể khác với các giới hạn mô hình của hình ([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height)) và có thể chứa tọa độ âm nếu nội dung đã render vượt ra ngoài gốc slide.
            
Giới hạn trực quan tính đến các khía cạnh liên quan tới quá trình render như biến đổi (ví dụ, quay), độ rộng nét và các góc nối, bố cục và tràn văn bản, hình học SmartArt, và các hiệu ứng bố cục khác ảnh hưởng đến diện mạo cuối cùng của hình sau khi render.
            
Các giới hạn được trả về không bị cắt theo hình chữ nhật slide.



### See Also
* class [`SummaryZoomSection`](/slides/python-net/vi/aspose.slides/summaryzoomsection)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
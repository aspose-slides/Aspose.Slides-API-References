---
title: get_visual_bounds method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.ink/inkactions/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Lấy giới hạn trực quan của hình dạng được tính dựa trên nội dung đã được vẽ.

### Trả về

Một [`RectangleF`](/slides/python-net/vi/aspose.slides/rectanglef) đại diện cho giới hạn trực quan của hình dạng trong tọa độ slide.



```python
def get_visual_bounds(self):
    ...
```


### Ghi chú

Hình chữ nhật trả về đại diện cho các giới hạn song song trục của toàn bộ nội dung do hình dạng tạo ra trong quá trình vẽ trong không gian tọa độ slide.

Các giới hạn này có thể khác với các giới hạn mô hình của hình dạng ([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height)) và có thể chứa các tọa độ âm nếu nội dung đã vẽ mở rộng ra ngoài gốc slide.

Các giới hạn trực quan tính đến các khía cạnh liên quan đến việc vẽ như biến đổi (ví dụ, quay), độ rộng nét và các mối nối, bố cục và tràn văn bản, hình học SmartArt, và các hiệu ứng bố cục khác ảnh hưởng đến giao diện cuối cùng của hình dạng.

Các giới hạn trả về không bị cắt theo hình chữ nhật slide.



### Xem thêm
* lớp [`InkActions`](/slides/python-net/vi/aspose.slides.ink/inkactions)
* lớp [`RectangleF`](/slides/python-net/vi/aspose.slides/rectanglef)
* mô-đun [`aspose.slides.ink`](/slides/python-net/vi/aspose.slides.ink)
* thư viện [`Aspose.Slides`](/slides/python-net)
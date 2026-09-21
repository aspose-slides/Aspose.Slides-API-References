---
title: get_visual_bounds method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/videoframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Lấy giới hạn trực quan của hình dạng được tính toán từ nội dung đã hiển thị của nó.

### Giá trị trả về

Một **aspose.slides.RectangleF** đại diện cho giới hạn trực quan của hình dạng trong tọa độ slide.



```python
def get_visual_bounds(self):
    ...
```


### Ghi chú

Hình chữ nhật trả về đại diện cho các giới hạn được căn trục của toàn bộ nội dung được hình dạng tạo ra trong quá trình hiển thị trong không gian tọa độ slide.

Các giới hạn này có thể khác với các giới hạn mô hình của hình dạng ([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height)) và có thể chứa tọa độ âm nếu nội dung đã hiển thị mở rộng ra ngoài gốc slide.

Giới hạn trực quan tính đến các khía cạnh liên quan đến việc hiển thị như biến đổi (ví dụ, quay), độ rộng nét và các nối, bố cục và tràn văn bản, hình học SmartArt, và các hiệu ứng bố cục khác ảnh hưởng đến diện mạo cuối cùng của hình dạng khi được hiển thị.

Các giới hạn trả về không bị cắt bớt theo hình chữ nhật slide.



### Xem thêm
* lớp [`VideoFrame`](/slides/python-net/vi/aspose.slides/videoframe)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
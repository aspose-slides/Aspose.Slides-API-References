---
title: get_visual_bounds method
second_title: Aspose.Slides cho Python qua Tham khảo API .NET
description: 
type: docs
url: /vi/aspose.slides/oleobjectframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Lấy giới hạn trực quan của hình dạng được tính toán từ nội dung đã hiển thị của nó.

### Trả về

Một **aspose.slides.RectangleF** đại diện cho giới hạn trực quan của hình dạng trong tọa độ slide.



```python
def get_visual_bounds(self):
    ...
```


### Ghi chú

Đoạn hình chữ nhật được trả về đại diện cho các giới hạn thẳng hàng trục của toàn bộ nội dung
             được hình dạng tạo ra trong quá trình render trong không gian tọa độ slide.
            
             Các giới hạn này có thể khác với các giới hạn mô hình của hình dạng
             ([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height))
             và có thể chứa các tọa độ âm nếu nội dung đã render mở rộng
             ra ngoài gốc slide.
            
             Các giới hạn trực quan cân nhắc các khía cạnh liên quan đến render như
             các phép biến đổi (ví dụ, quay), độ rộng nét và các nối,
             bố cục văn bản và tràn, hình học SmartArt, và các hiệu ứng bố cục khác
             ảnh hưởng đến giao diện cuối cùng đã render của hình dạng.
            
             Các giới hạn được trả về không bị cắt theo hình chữ nhật slide.



### Xem thêm
* lớp [`OleObjectFrame`](/slides/python-net/vi/aspose.slides/oleobjectframe)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
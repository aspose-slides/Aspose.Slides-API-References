---
title: add_section_zoom_frame method
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides/ishapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
Tạo một khung Section Zoom mới và thêm nó vào cuối bộ sưu tập shape.

### Giá trị trả về

Đối tượng [`ISectionZoomFrame`](/slides/python-net/vi/aspose.slides/isectionzoomframe) mới được tạo.



```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| x | **float** | Tọa độ x của khung Section Zoom mới, tính bằng points. |
| y | **float** | Tọa độ y của khung Section Zoom mới, tính bằng points. |
| width | **float** | Chiều rộng của khung Section Zoom mới, tính bằng points. |
| height | **float** | Chiều cao của khung Section Zoom mới, tính bằng points. |
| section | [`ISection`](/slides/python-net/vi/aspose.slides/isection) | Đối tượng [`ISection`](/slides/python-net/vi/aspose.slides/isection) được tham chiếu bởi khung Section Zoom; phải thuộc về bản trình chiếu này và chứa ít nhất một slide. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Ném ra nếu phần được tham chiếu không thuộc bản trình chiếu hiện tại hoặc không chứa slide nào. |


## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
Tạo một khung Section Zoom mới với hình ảnh đã định sẵn và thêm nó vào cuối bộ sưu tập shape.

### Giá trị trả về

Đối tượng [`ISectionZoomFrame`](/slides/python-net/vi/aspose.slides/isectionzoomframe) mới được tạo.



```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| x | **float** | Tọa độ x của khung Section Zoom mới, tính bằng points. |
| y | **float** | Tọa độ y của khung Section Zoom mới, tính bằng points. |
| width | **float** | Chiều rộng của khung Section Zoom mới, tính bằng points. |
| height | **float** | Chiều cao của khung Section Zoom mới, tính bằng points. |
| section | [`ISection`](/slides/python-net/vi/aspose.slides/isection) | Đối tượng [`ISection`](/slides/python-net/vi/aspose.slides/isection) được tham chiếu bởi khung Section Zoom; phải thuộc về bản trình chiếu này và chứa ít nhất một slide. |
| image | [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage) | Đối tượng [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage) để hiển thị trong khung Section Zoom. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Ném ra nếu phần được tham chiếu không thuộc bản trình chiếu hiện tại hoặc không chứa slide nào. |



### Xem thêm
* lớp [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage)
* lớp [`ISection`](/slides/python-net/vi/aspose.slides/isection)
* lớp [`ISectionZoomFrame`](/slides/python-net/vi/aspose.slides/isectionzoomframe)
* lớp [`IShapeCollection`](/slides/python-net/vi/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
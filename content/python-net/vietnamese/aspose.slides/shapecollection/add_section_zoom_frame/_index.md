---
title: add_section_zoom_frame method
second_title: Tài liệu tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/shapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
Tạo một khung Section Zoom mới và thêm nó vào cuối bộ sưu tập shape.

### Returns

Đối tượng [`ISectionZoomFrame`](/slides/python-net/vi/aspose.slides/isectionzoomframe) mới được tạo.



```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| x | **float** | Tọa độ x của khung Section Zoom mới, tính bằng điểm. |
| y | **float** | Tọa độ y của khung Section Zoom mới, tính bằng điểm. |
| width | **float** | Chiều rộng của khung Section Zoom mới, tính bằng điểm. |
| height | **float** | Chiều cao của khung Section Zoom mới, tính bằng điểm. |
| section | [`ISection`](/slides/python-net/vi/aspose.slides/isection) | [`ISection`](/slides/python-net/vi/aspose.slides/isection) được tham chiếu bởi khung Section Zoom; <br/><br/>phải thuộc vào bài thuyết trình này và chứa ít nhất một slide. |

### Exceptions

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Bị ném nếu phần được tham chiếu không thuộc bài thuyết trình hiện tại hoặc không chứa slide nào. |


## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
Tạo một khung Section Zoom mới với ảnh được định trước và thêm nó vào cuối bộ sưu tập shape.

### Returns

Đối tượng [`ISectionZoomFrame`](/slides/python-net/vi/aspose.slides/isectionzoomframe) mới được tạo.



```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| x | **float** | Tọa độ x của khung Section Zoom mới, tính bằng điểm. |
| y | **float** | Tọa độ y của khung Section Zoom mới, tính bằng điểm. |
| width | **float** | Chiều rộng của khung Section Zoom mới, tính bằng điểm. |
| height | **float** | Chiều cao của khung Section Zoom mới, tính bằng điểm. |
| section | [`ISection`](/slides/python-net/vi/aspose.slides/isection) | [`ISection`](/slides/python-net/vi/aspose.slides/isection) được tham chiếu bởi khung Section Zoom; <br/><br/>phải thuộc vào bài thuyết trình này và chứa ít nhất một slide. |
| image | [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage) | [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage) để hiển thị trong khung Section Zoom. |

### Exceptions

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Bị ném nếu phần được tham chiếu không thuộc bài thuyết trình hiện tại hoặc không chứa slide nào. |



### See Also
* lớp [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage)
* lớp [`ISection`](/slides/python-net/vi/aspose.slides/isection)
* lớp [`ISectionZoomFrame`](/slides/python-net/vi/aspose.slides/isectionzoomframe)
* lớp [`ShapeCollection`](/slides/python-net/vi/aspose.slides/shapecollection)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
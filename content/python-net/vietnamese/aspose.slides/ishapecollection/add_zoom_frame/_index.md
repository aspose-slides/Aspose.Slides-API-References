---
title: add_zoom_frame method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/ishapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
Tạo một khung Zoom mới và thêm nó vào cuối bộ sưu tập shape.

### Returns

Đối tượng mới tạo [`IZoomFrame`](/slides/python-net/vi/aspose.slides/izoomframe).

```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| x | **float** | Tọa độ x của khung Zoom mới, tính bằng điểm. |
| y | **float** | Tọa độ y của khung Zoom mới, tính bằng điểm. |
| width | **float** | Chiều rộng của khung Zoom mới, tính bằng điểm. |
| height | **float** | Chiều cao của khung Zoom mới, tính bằng điểm. |
| slide | [`ISlide`](/slides/python-net/vi/aspose.slides/islide) | [`ISlide`](/slides/python-net/vi/aspose.slides/islide) được tham chiếu bởi khung Zoom;<br/><br/>            phải thuộc về bản trình bày này. |

### Exceptions

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Bị ném nếu slide được tham chiếu không thuộc về bản trình bày hiện tại. |

## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
Tạo một khung Zoom mới và thêm nó vào cuối bộ sưu tập shape.

### Returns

Đối tượng mới tạo [`IZoomFrame`](/slides/python-net/vi/aspose.slides/izoomframe).

```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| x | **float** | Tọa độ x của khung Zoom mới, tính bằng điểm. |
| y | **float** | Tọa độ y của khung Zoom mới, tính bằng điểm. |
| width | **float** | Chiều rộng của khung Zoom mới, tính bằng điểm. |
| height | **float** | Chiều cao của khung Zoom mới, tính bằng điểm. |
| slide | [`ISlide`](/slides/python-net/vi/aspose.slides/islide) | [`ISlide`](/slides/python-net/vi/aspose.slides/islide) được tham chiếu bởi khung Zoom;<br/><br/>            phải thuộc về bản trình bày này. |
| image | [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage) | Hình ảnh cho slide được tham chiếu [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage). |

### Exceptions

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Bị ném nếu slide được tham chiếu không thuộc về bản trình bày hiện tại. |

### See Also
* lớp [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage)
* lớp [`IShapeCollection`](/slides/python-net/vi/aspose.slides/ishapecollection)
* lớp [`ISlide`](/slides/python-net/vi/aspose.slides/islide)
* lớp [`IZoomFrame`](/slides/python-net/vi/aspose.slides/izoomframe)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
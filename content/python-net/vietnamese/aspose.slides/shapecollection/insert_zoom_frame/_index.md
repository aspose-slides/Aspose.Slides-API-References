---
title: insert_zoom_frame method
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides/shapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
Tạo một Zoom frame mới và chèn nó vào bộ sưu tập shape tại chỉ mục được chỉ định.

### Trả về

[`IZoomFrame`](/slides/python-net/vi/aspose.slides/izoomframe) mới được tạo.



```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ mục bắt đầu từ 0 tại đó sẽ chèn Zoom frame. |
| x | **float** | Tọa độ x của Zoom frame mới, tính bằng điểm. |
| y | **float** | Tọa độ y của Zoom frame mới, tính bằng điểm. |
| width | **float** | Chiều rộng của Zoom frame mới, tính bằng điểm. |
| height | **float** | Chiều cao của Zoom frame mới, tính bằng điểm. |
| slide | [`ISlide`](/slides/python-net/vi/aspose.slides/islide) | [`ISlide`](/slides/python-net/vi/aspose.slides/islide) được Zoom frame tham chiếu. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Bị ném nếu slide được tham chiếu không thuộc về bản trình bày hiện tại. |


## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
Tạo một Zoom frame mới với hình ảnh được xác định trước và chèn nó vào bộ sưu tập shape
            tại chỉ mục được chỉ định.

### Trả về

[`IZoomFrame`](/slides/python-net/vi/aspose.slides/izoomframe) mới được tạo.



```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ mục bắt đầu từ 0 tại đó sẽ chèn Zoom frame. |
| x | **float** | Tọa độ x của Zoom frame mới, tính bằng điểm. |
| y | **float** | Tọa độ y của Zoom frame mới, tính bằng điểm. |
| width | **float** | Chiều rộng của Zoom frame mới, tính bằng điểm. |
| height | **float** | Chiều cao của Zoom frame mới, tính bằng điểm. |
| slide | [`ISlide`](/slides/python-net/vi/aspose.slides/islide) | [`ISlide`](/slides/python-net/vi/aspose.slides/islide) được Zoom frame tham chiếu. |
| image | [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage) | Hình ảnh cho slide được tham chiếu [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage). |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Bị ném nếu slide được tham chiếu không thuộc về bản trình bày hiện tại. |



### Xem thêm
* lớp [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage)
* lớp [`ISlide`](/slides/python-net/vi/aspose.slides/islide)
* lớp [`IZoomFrame`](/slides/python-net/vi/aspose.slides/izoomframe)
* lớp [`ShapeCollection`](/slides/python-net/vi/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
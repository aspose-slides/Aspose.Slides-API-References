---
title: insert_zoom_frame method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/ishapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
Tạo một khung Zoom mới và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định.

### Trả về

Đối tượng [`IZoomFrame`](/slides/python-net/vi/aspose.slides/izoomframe) mới được tạo.



```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ mục dựa trên 0 tại đó sẽ chèn khung Zoom. |
| x | **float** | Tọa độ x của khung Zoom mới, tính bằng điểm. |
| y | **float** | Tọa độ y của khung Zoom mới, tính bằng điểm. |
| width | **float** | Chiều rộng của khung Zoom mới, tính bằng điểm. |
| height | **float** | Chiều cao của khung Zoom mới, tính bằng điểm. |
| slide | [`ISlide`](/slides/python-net/vi/aspose.slides/islide) | Đối tượng [`ISlide`](/slides/python-net/vi/aspose.slides/islide) được khung Zoom tham chiếu. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Bị ném nếu slide được tham chiếu không thuộc về bản trình bày hiện tại. |


## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
Tạo một khung Zoom mới với hình ảnh được định sẵn và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định.

### Trả về

Đối tượng [`IZoomFrame`](/slides/python-net/vi/aspose.slides/izoomframe) mới được tạo.



```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ mục dựa trên 0 tại đó sẽ chèn khung Zoom. |
| x | **float** | Tọa độ x của khung Zoom mới, tính bằng điểm. |
| y | **float** | Tọa độ y của khung Zoom mới, tính bằng điểm. |
| width | **float** | Chiều rộng của khung Zoom mới, tính bằng điểm. |
| height | **float** | Chiều cao của khung Zoom mới, tính bằng điểm. |
| slide | [`ISlide`](/slides/python-net/vi/aspose.slides/islide) | Đối tượng [`ISlide`](/slides/python-net/vi/aspose.slides/islide) được khung Zoom tham chiếu. |
| image | [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage) | Hình ảnh cho slide được tham chiếu [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage). |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Bị ném nếu slide được tham chiếu không thuộc về bản trình bày hiện tại. |



### Xem thêm
* lớp [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage)
* lớp [`IShapeCollection`](/slides/python-net/vi/aspose.slides/ishapecollection)
* lớp [`ISlide`](/slides/python-net/vi/aspose.slides/islide)
* lớp [`IZoomFrame`](/slides/python-net/vi/aspose.slides/izoomframe)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
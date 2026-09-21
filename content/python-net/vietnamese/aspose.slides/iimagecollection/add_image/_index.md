---
title: add_image method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/iimagecollection/add_image/
weight: 10
---
## add_image(self, image) {#iimage}
Thêm một hình ảnh vào bản trình bày.

### Trả về

Đã thêm hình ảnh.



```python
def add_image(self, image):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/vi/aspose.slides/iimage) | Hình ảnh cần thêm. |

### Ghi chú

Phương thức này chuyển đổi các file metafile WMF/EMF sang hình ảnh PNG raster trước khi chèn vào bản trình bày.


## add_image(self, stream) {#iorawiobase}
Thêm một hình ảnh vào bản trình bày từ luồng.

### Trả về

Đã thêm hình ảnh.



```python
def add_image(self, stream):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| stream | **io.RawIOBase** | Luồng để thêm hình ảnh từ. |

### Ghi chú

Phương thức này có thể thêm các file metafile WMF/EMF vào bản trình bày mà không chuyển chúng sang hình ảnh PNG raster.


## add_image(self, buffer) {#bytes}
Thêm một hình ảnh vào bản trình bày từ bộ đệm đã chỉ định.

### Trả về

Đã thêm hình ảnh.



```python
def add_image(self, buffer):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| buffer | **bytes** | Bộ đệm. |


## add_image(self, image_source) {#ippimage}
Thêm một bản sao của hình ảnh từ bản trình bày khác.

### Trả về

Đã thêm hình ảnh.



```python
def add_image(self, image_source):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage) | Hình ảnh nguồn. |


## add_image(self, svg_image) {#isvgimage}
Thêm một hình ảnh vào bản trình bày từ đối tượng SVG.

### Trả về

Đã thêm hình ảnh.



```python
def add_image(self, svg_image):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/vi/aspose.slides/isvgimage) | Đối tượng SVG [`ISvgImage`](/slides/python-net/vi/aspose.slides/isvgimage) |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Bị ném khi tham số svgImage là None. |


## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Tạo và thêm một hình ảnh vào bản trình bày từ luồng.

### Trả về

Đã thêm [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage).



```python
def add_image(self, stream, loading_stream_behavior):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| stream | **io.RawIOBase** | Luồng để thêm tệp hình ảnh từ. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/vi/aspose.slides/loadingstreambehavior) | Hành vi sẽ được áp dụng cho luồng. |



### Xem thêm
* lớp [`IImage`](/slides/python-net/vi/aspose.slides/iimage)
* lớp [`IImageCollection`](/slides/python-net/vi/aspose.slides/iimagecollection)
* lớp [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage)
* lớp [`ISvgImage`](/slides/python-net/vi/aspose.slides/isvgimage)
* liệt kê [`LoadingStreamBehavior`](/slides/python-net/vi/aspose.slides/loadingstreambehavior)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
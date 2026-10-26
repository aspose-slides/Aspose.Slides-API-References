---
title: save method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/iimage/save/
weight: 10
---
## save(self, filename) {#str}
Lưu hình ảnh vào tệp.


```python
def save(self, filename):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| filename | **str** | Đường dẫn tới tệp mà hình ảnh sẽ được lưu. |


## save(self, filename, format) {#str-imageformat}
Lưu hình ảnh vào tệp với định dạng được chỉ định.


```python
def save(self, filename, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| filename | **str** | Đường dẫn tới tệp mà hình ảnh sẽ được lưu. |
| format | [`ImageFormat`](/slides/python-net/vi/aspose.slides/imageformat) | Định dạng hình ảnh. |


## save(self, stream, format) {#iorawiobase-imageformat}
Lưu hình ảnh vào luồng với định dạng được chỉ định.


```python
def save(self, stream, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Luồng mà hình ảnh sẽ được lưu. |
| format | [`ImageFormat`](/slides/python-net/vi/aspose.slides/imageformat) | Định dạng hình ảnh. |


## save(self, filename, format, quality) {#str-imageformat-int}
Lưu hình ảnh vào tệp với định dạng và chất lượng được chỉ định.


```python
def save(self, filename, format, quality):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| filename | **str** | Đường dẫn tới tệp mà hình ảnh sẽ được lưu. |
| format | [`ImageFormat`](/slides/python-net/vi/aspose.slides/imageformat) | Định dạng hình ảnh. |
| quality | **int** | Chất lượng của ảnh đã lưu (0 đến 100).  <br/><br/>            Tham số này chỉ ảnh hưởng đến việc lưu trong [`ImageFormat.JPEG`](/slides/python-net/vi/aspose.slides/imageformat/JPEG); với các định dạng khác, nó bị bỏ qua. |


## save(self, stream, format, quality) {#iorawiobase-imageformat-int}
Lưu hình ảnh vào luồng với định dạng và chất lượng được chỉ định.


```python
def save(self, stream, format, quality):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Luồng mà hình ảnh sẽ được lưu. |
| format | [`ImageFormat`](/slides/python-net/vi/aspose.slides/imageformat) | Định dạng hình ảnh. |
| quality | **int** | Chất lượng của ảnh đã lưu (0 đến 100).  <br/><br/>            Tham số này chỉ ảnh hưởng đến việc lưu trong [`ImageFormat.JPEG`](/slides/python-net/vi/aspose.slides/imageformat/JPEG); với các định dạng khác, nó bị bỏ qua. |



### See Also
* class [`IImage`](/slides/python-net/vi/aspose.slides/iimage)
* enumeration [`ImageFormat`](/slides/python-net/vi/aspose.slides/imageformat)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
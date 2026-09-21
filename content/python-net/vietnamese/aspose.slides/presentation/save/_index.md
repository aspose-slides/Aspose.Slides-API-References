---
title: save method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/presentation/save/
weight: 90
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
Lưu tất cả các slide của một bản trình chiếu thành một tập hợp các tệp đại diện cho markup XAML.


```python
def save(self, options):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/vi/aspose.slides.export.xaml/ixamloptions) | Các tùy chọn định dạng XAML. |


## save(self, fname, format) {#str-asposeslidesexportsaveformat}
Lưu tất cả các slide của một bản trình chiếu vào một tệp với định dạng đã chỉ định.


```python
def save(self, fname, format):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| fname | **str** | Đường dẫn tới tệp được tạo. |
| format | [`SaveFormat`](/slides/python-net/vi/aspose.slides.export/saveformat) | Định dạng của dữ liệu đã xuất. |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
Lưu tất cả các slide của một bản trình chiếu vào một luồng với định dạng đã chỉ định.


```python
def save(self, stream, format):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| stream | **io.RawIOBase** | Luồng đầu ra. |
| format | [`SaveFormat`](/slides/python-net/vi/aspose.slides.export/saveformat) | Định dạng của dữ liệu đã xuất. |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}


```python
def save(self, fname, format, options):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| fname | **str** |  |
| format | [`SaveFormat`](/slides/python-net/vi/aspose.slides.export/saveformat) |  |
| options | [`ISaveOptions`](/slides/python-net/vi/aspose.slides.export/isaveoptions) |  |


## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Lưu tất cả các slide của một bản trình chiếu vào một luồng với định dạng đã chỉ định và các tùy chọn bổ sung.


```python
def save(self, stream, format, options):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| stream | **io.RawIOBase** | Luồng đầu ra. |
| format | [`SaveFormat`](/slides/python-net/vi/aspose.slides.export/saveformat) | Định dạng của dữ liệu đã xuất. |
| options | [`ISaveOptions`](/slides/python-net/vi/aspose.slides.export/isaveoptions) | Các tùy chọn định dạng bổ sung. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | Nếu bạn cố lưu tệp được mã hóa trong <br/>                định dạng không phải Office 2007-2010 |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
Lưu các slide được chỉ định của một bản trình chiếu vào một tệp với định dạng đã chỉ định và giữ lại số trang.


```python
def save(self, fname, slides, format):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| fname | **str** | Đường dẫn tới tệp được tạo. |
| slides | **List[int]** | Mảng vị trí slide, bắt đầu từ 1. |
| format | [`SaveFormat`](/slides/python-net/vi/aspose.slides.export/saveformat) | Định dạng của dữ liệu đã xuất. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Khi tham số stream hoặc slides là None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Khi tham số slides chứa số trang không đúng. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Khi sử dụng SaveFormat không được hỗ trợ, ví dụ PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
Lưu các slide được chỉ định của một bản trình chiếu vào một luồng với định dạng đã chỉ định và giữ lại số trang.


```python
def save(self, stream, slides, format):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| stream | **io.RawIOBase** | Luồng đầu ra. |
| slides | **List[int]** | Mảng vị trí slide, bắt đầu từ 1. |
| format | [`SaveFormat`](/slides/python-net/vi/aspose.slides.export/saveformat) | Định dạng của dữ liệu đã xuất. |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Lưu các slide được chỉ định của một bản trình chiếu vào một tệp với định dạng đã chỉ định và giữ lại số trang.


```python
def save(self, fname, slides, format, options):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| fname | **str** | Đường dẫn tới tệp được tạo. |
| slides | **List[int]** | Mảng vị trí slide, bắt đầu từ 1. |
| format | [`SaveFormat`](/slides/python-net/vi/aspose.slides.export/saveformat) | Định dạng của dữ liệu đã xuất. |
| options | [`ISaveOptions`](/slides/python-net/vi/aspose.slides.export/isaveoptions) | Các tùy chọn định dạng bổ sung. |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Lưu các slide được chỉ định của một bản trình chiếu vào một luồng với định dạng đã chỉ định và giữ lại số trang.


```python
def save(self, stream, slides, format, options):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| stream | **io.RawIOBase** | Luồng đầu ra. |
| slides | **List[int]** | Mảng vị trí slide, bắt đầu từ 1. |
| format | [`SaveFormat`](/slides/python-net/vi/aspose.slides.export/saveformat) | Định dạng của dữ liệu đã xuất. |
| options | [`ISaveOptions`](/slides/python-net/vi/aspose.slides.export/isaveoptions) | Các tùy chọn định dạng bổ sung. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Khi tham số stream hoặc slides là None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Khi tham số slides chứa số trang không đúng. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Khi sử dụng SaveFormat không được hỗ trợ, ví dụ PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



### Xem Thêm
* lớp [`ISaveOptions`](/slides/python-net/vi/aspose.slides.export/isaveoptions)
* lớp [`IXamlOptions`](/slides/python-net/vi/aspose.slides.export.xaml/ixamloptions)
* lớp [`Presentation`](/slides/python-net/vi/aspose.slides/presentation)
* enumeration [`SaveFormat`](/slides/python-net/vi/aspose.slides.export/saveformat)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
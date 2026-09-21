---
title: save method
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides/ipresentation/save/
weight: 80
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
Lưu tất cả các slide của một bài thuyết trình vào một tập hợp các tệp đại diện cho mã XAML markup.


```python
def save(self, options):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/vi/aspose.slides.export.xaml/ixamloptions) | Các tùy chọn định dạng XAML. |


## save(self, fname, format) {#str-asposeslidesexportsaveformat}
Lưu tất cả các slide của một bài thuyết trình vào một tệp với định dạng được chỉ định.


```python
def save(self, fname, format):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| fname | **str** | Đường dẫn tới tệp được tạo. |
| format | [`SaveFormat`](/slides/python-net/vi/aspose.slides.export/saveformat) | Định dạng của dữ liệu được xuất. |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
Lưu tất cả các slide của một bài thuyết trình vào luồng với định dạng được chỉ định.


```python
def save(self, stream, format):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| stream | **io.RawIOBase** | Luồng đầu ra. |
| format | [`SaveFormat`](/slides/python-net/vi/aspose.slides.export/saveformat) | Định dạng của dữ liệu được xuất. |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Lưu tất cả các slide của một bài thuyết trình vào một tệp với định dạng được chỉ định và các tùy chọn bổ sung.


```python
def save(self, fname, format, options):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| fname | **str** | Đường dẫn tới tệp được tạo. |
| format | [`SaveFormat`](/slides/python-net/vi/aspose.slides.export/saveformat) | Định dạng của dữ liệu được xuất. |
| options | [`ISaveOptions`](/slides/python-net/vi/aspose.slides.export/isaveoptions) | Các tùy chọn định dạng bổ sung. |


## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Lưu tất cả các slide của một bài thuyết trình vào luồng với định dạng được chỉ định và các tùy chọn bổ sung.


```python
def save(self, stream, format, options):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| stream | **io.RawIOBase** | Luồng đầu ra. |
| format | [`SaveFormat`](/slides/python-net/vi/aspose.slides.export/saveformat) | Định dạng của dữ liệu được xuất. |
| options | [`ISaveOptions`](/slides/python-net/vi/aspose.slides.export/isaveoptions) | Các tùy chọn định dạng bổ sung. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | Nếu bạn cố gắng lưu tệp được mã hoá ở định dạng <br/>            none Office 2007-2010 |

## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
Lưu các slide được chỉ định của một bài thuyết trình vào một tệp với định dạng được chỉ định.


```python
def save(self, fname, slides, format):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| fname | **str** | Đường dẫn tới tệp được tạo. |
| slides | **List[int]** | Mảng chứa vị trí các slide, bắt đầu từ 1. |
| format | [`SaveFormat`](/slides/python-net/vi/aspose.slides.export/saveformat) | Định dạng của dữ liệu được xuất. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Khi tham số stream hoặc slides là None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Khi tham số slides chứa các số trang không đúng. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Khi sử dụng SaveFormat không được hỗ trợ, ví dụ: PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
Lưu các slide được chỉ định của một bài thuyết trình vào luồng với định dạng được chỉ định.


```python
def save(self, stream, slides, format):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| stream | **io.RawIOBase** | Luồng đầu ra. |
| slides | **List[int]** | Mảng chứa vị trí các slide, bắt đầu từ 1. |
| format | [`SaveFormat`](/slides/python-net/vi/aspose.slides.export/saveformat) | Định dạng của dữ liệu được xuất. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Khi tham số stream hoặc slides là None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Khi tham số slides chứa các số trang không đúng. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Khi sử dụng SaveFormat không được hỗ trợ, ví dụ: PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Lưu các slide được chỉ định của một bài thuyết trình vào một tệp với định dạng được chỉ định.


```python
def save(self, fname, slides, format, options):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| fname | **str** | Đường dẫn tới tệp được tạo. |
| slides | **List[int]** | Mảng chứa vị trí các slide, bắt đầu từ 1. |
| format | [`SaveFormat`](/slides/python-net/vi/aspose.slides.export/saveformat) | Định dạng của dữ liệu được xuất. |
| options | [`ISaveOptions`](/slides/python-net/vi/aspose.slides.export/isaveoptions) | Các tùy chọn định dạng bổ sung. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Khi tham số stream hoặc slides là None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Khi tham số slides chứa các số trang không đúng. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Khi sử dụng SaveFormat không được hỗ trợ, ví dụ: PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Lưu các slide được chỉ định của một bài thuyết trình vào luồng với định dạng được chỉ định.


```python
def save(self, stream, slides, format, options):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| stream | **io.RawIOBase** | Luồng đầu ra. |
| slides | **List[int]** | Mảng chứa vị trí các slide, bắt đầu từ 1. |
| format | [`SaveFormat`](/slides/python-net/vi/aspose.slides.export/saveformat) | Định dạng của dữ liệu được xuất. |
| options | [`ISaveOptions`](/slides/python-net/vi/aspose.slides.export/isaveoptions) | Các tùy chọn định dạng bổ sung. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Khi tham số stream hoặc slides là None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Khi tham số slides chứa các số trang không đúng. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Khi sử dụng SaveFormat không được hỗ trợ, ví dụ: PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



### Xem thêm
* lớp [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation)
* lớp [`ISaveOptions`](/slides/python-net/vi/aspose.slides.export/isaveoptions)
* lớp [`IXamlOptions`](/slides/python-net/vi/aspose.slides.export.xaml/ixamloptions)
* liệt kê [`SaveFormat`](/slides/python-net/vi/aspose.slides.export/saveformat)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
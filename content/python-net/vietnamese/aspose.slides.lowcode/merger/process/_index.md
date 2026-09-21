---
title: process method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.lowcode/merger/process/
weight: 10
---
## process(input_file_names, output_file_name) {#liststr-str}
Hợp nhất nhiều bản trình chiếu PowerPoint có cùng định dạng thành một tệp trình chiếu duy nhất.

```python
@staticmethod
def process(input_file_names, output_file_name):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| input_file_names | **List[str]** | Một mảng các tên tệp trình chiếu đầu vào. |
| output_file_name | **str** | Tên tệp đầu ra của tệp trình chiếu đã hợp nhất. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Được ném khi tên tệp đầu vào không hợp lệ hoặc định dạng không khớp. |

## process(input_file_names, output_stream) {#liststr-iorawiobase}
Hợp nhất nhiều bản trình chiếu PowerPoint có cùng định dạng thành một tệp trình chiếu duy nhất.

```python
@staticmethod
def process(input_file_names, output_stream):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| input_file_names | **List[str]** | Một mảng các tên tệp trình chiếu đầu vào. |
| output_stream | **io.RawIOBase** | Luồng đầu ra. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Được ném khi tên tệp đầu vào không hợp lệ hoặc định dạng không khớp. |

## process(input_file_names, output_file_name, options) {#liststr-str-asposeslidesexportisaveoptions}
Hợp nhất nhiều bản trình chiếu PowerPoint có cùng định dạng thành một tệp trình chiếu duy nhất.

```python
@staticmethod
def process(input_file_names, output_file_name, options):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| input_file_names | **List[str]** | Một mảng các tên tệp trình chiếu đầu vào. |
| output_file_name | **str** | Tên tệp đầu ra của tệp trình chiếu đã hợp nhất. |
| options | [`ISaveOptions`](/slides/python-net/vi/aspose.slides.export/isaveoptions) | Các tùy chọn bổ sung xác định cách lưu bản trình chiếu đã hợp nhất. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Được ném khi tên tệp đầu vào không hợp lệ hoặc định dạng không khớp. |

## process(input_file_names, output_stream, options) {#liststr-iorawiobase-asposeslidesexportisaveoptions}
Hợp nhất nhiều bản trình chiếu PowerPoint có cùng định dạng thành một tệp trình chiếu duy nhất.

```python
@staticmethod
def process(input_file_names, output_stream, options):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| input_file_names | **List[str]** | Một mảng các tên tệp trình chiếu đầu vào. |
| output_stream | **io.RawIOBase** | Luồng đầu ra. |
| options | [`ISaveOptions`](/slides/python-net/vi/aspose.slides.export/isaveoptions) | Các tùy chọn bổ sung xác định cách lưu bản trình chiếu đã hợp nhất. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Được ném khi tên tệp đầu vào không hợp lệ hoặc định dạng không khớp. |

### Xem thêm
* lớp [`ISaveOptions`](/slides/python-net/vi/aspose.slides.export/isaveoptions)
* lớp [`Merger`](/slides/python-net/vi/aspose.slides.lowcode/merger)
* module [`aspose.slides.lowcode`](/slides/python-net/vi/aspose.slides.lowcode)
* library [`Aspose.Slides`](/slides/python-net)
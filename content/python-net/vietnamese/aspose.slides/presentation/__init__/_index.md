---
title: Presentation constructor
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/presentation/__init__/
weight: 10
---
## __init__(self) {#}
Phương thức khởi tạo này tạo một bài thuyết trình mới từ đầu.
            Bài thuyết trình được tạo có một slide trống.


```python
def __init__(self):
    ...
```



## __init__(self, load_options) {#loadoptions}
Phương thức khởi tạo này tạo một bài thuyết trình mới từ đầu.
            Bài thuyết trình được tạo có một slide trống.


```python
def __init__(self, load_options):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| load_options | [`LoadOptions`](/slides/python-net/vi/aspose.slides/loadoptions) | Các tùy chọn tải bổ sung. |


## __init__(self, stream) {#iorawiobase}
Phương thức khởi tạo này là cơ chế chính để đọc một Bài thuyết trình hiện có.


```python
def __init__(self, stream):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| stream | **io.RawIOBase** | Luồng nhập. |


## __init__(self, file) {#str}
Phương thức khởi tạo này nhận một đường dẫn tệp nguồn, từ đó
             nội dung của Bài thuyết trình được đọc.


```python
def __init__(self, file):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| file | **str** | Tập tin nhập. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Được ném khi tập tin nhập có độ dài bằng không |


## __init__(self, stream, load_options) {#iorawiobase-loadoptions}
Phương thức khởi tạo này là cơ chế chính để đọc một Bài thuyết trình hiện có.


```python
def __init__(self, stream, load_options):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| stream | **io.RawIOBase** | Luồng nhập. |
| load_options | [`LoadOptions`](/slides/python-net/vi/aspose.slides/loadoptions) | Các tùy chọn tải bổ sung. |


## __init__(self, file, load_options) {#str-loadoptions}
Phương thức khởi tạo này nhận một đường dẫn tệp nguồn, từ đó
            nội dung của Bài thuyết trình được đọc.


```python
def __init__(self, file, load_options):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| file | **str** | Tập tin nhập. |
| load_options | [`LoadOptions`](/slides/python-net/vi/aspose.slides/loadoptions) | Các tùy chọn tải bổ sung. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Được ném khi tập tin nhập có độ dài bằng không |



### Xem thêm
* lớp [`LoadOptions`](/slides/python-net/vi/aspose.slides/loadoptions)
* lớp [`Presentation`](/slides/python-net/vi/aspose.slides/presentation)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
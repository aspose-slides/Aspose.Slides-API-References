---
title: add method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/captionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
Thêm phụ đề đóng WebVTT vào cuối bộ sưu tập.

### Trả về

Đối tượng [`ICaptions`](/slides/python-net/vi/aspose.slides/icaptions) đã được thêm.



```python
def add(self, label, file_path):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| label | **str** | Nhãn của phụ đề đóng. |
| file_path | **str** | Đường dẫn tới tệp WebVTT. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Bị ném nếu `file_path` là `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Bị ném nếu `file_path` rỗng. |


## add(self, label, stream) {#str-iorawiobase}
Thêm phụ đề đóng WebVTT vào cuối bộ sưu tập từ một luồng.

### Trả về

Đối tượng [`ICaptions`](/slides/python-net/vi/aspose.slides/icaptions) đã được thêm.



```python
def add(self, label, stream):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| label | **str** | Nhãn của phụ đề đóng. |
| stream | **io.RawIOBase** | Luồng đầu vào chứa dữ liệu ở định dạng WebVTT. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Bị ném nếu `stream` là `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Bị ném nếu dữ liệu đầu vào không phải định dạng WebVTT. |



### Xem thêm
* lớp [`CaptionsCollection`](/slides/python-net/vi/aspose.slides/captionscollection)
* lớp [`ICaptions`](/slides/python-net/vi/aspose.slides/icaptions)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
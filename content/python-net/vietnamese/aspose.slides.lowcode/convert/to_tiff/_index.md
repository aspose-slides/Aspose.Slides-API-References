---
title: to_tiff method
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides.lowcode/convert/to_tiff/
weight: 60
---
## to_tiff(pres, output_file_name) {#presentation-str}
Chuyển đổi bản trình chiếu đầu vào thành một tập các hình ảnh định dạng TIFF.  
Nếu tên tệp đầu ra được chỉ định là "myPath/myFilename.tiff", kết quả sẽ được lưu thành một tập các tệp "myPath/myFilename_N.tiff", trong đó N là số slide.

```python
@staticmethod
def to_tiff(pres, output_file_name):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/vi/aspose.slides/presentation) | Bản trình chiếu đầu vào. |
| output_file_name | **str** | Tên tệp đầu ra. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

## to_tiff(pres, output_file_name, options, multipage) {#presentation-str-asposeslidesexportitiffoptions-bool}
Chuyển đổi bản trình chiếu đầu vào sang định dạng TIFF với các tùy chọn tùy chỉnh.  
Nếu tên tệp đầu ra được chỉ định là "myPath/myFilename.tiff" và `multipage` là `false`, kết quả sẽ được lưu thành một tập các tệp "myPath/myFilename_N.tiff", trong đó N là số slide.  
Ngược lại, nếu `multipage` là `true`, kết quả sẽ là một tài liệu đa trang "myPath/myFilename.tiff".

```python
@staticmethod
def to_tiff(pres, output_file_name, options, multipage):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/vi/aspose.slides/presentation) | Bản trình chiếu đầu vào. |
| output_file_name | **str** | Tên tệp đầu ra. |
| options | [`ITiffOptions`](/slides/python-net/vi/aspose.slides.export/itiffoptions) | Các tùy chọn lưu TIFF. |
| multipage | **bool** | Xác định xem tài liệu TIFF được tạo có phải là đa trang hay không. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

### Xem thêm
* lớp [`Convert`](/slides/python-net/vi/aspose.slides.lowcode/convert)
* lớp [`ITiffOptions`](/slides/python-net/vi/aspose.slides.export/itiffoptions)
* lớp [`Presentation`](/slides/python-net/vi/aspose.slides/presentation)
* module [`aspose.slides.lowcode`](/slides/python-net/vi/aspose.slides.lowcode)
* thư viện [`Aspose.Slides`](/slides/python-net)
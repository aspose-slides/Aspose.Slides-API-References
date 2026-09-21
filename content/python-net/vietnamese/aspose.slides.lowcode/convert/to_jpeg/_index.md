---
title: to_jpeg method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.lowcode/convert/to_jpeg/
weight: 20
---
## to_jpeg(pres, output_file_name) {#presentation-str}
Chuyển đổi bản trình bày đầu vào thành một tập hợp các hình ảnh định dạng JPEG.  
Nếu tên tệp đầu ra được cung cấp dưới dạng "myPath/myFilename.jpeg", 
kết quả sẽ được lưu dưới dạng một tập hợp các tệp "myPath/myFilename_N.jpeg", trong đó N là số slide.


```python
@staticmethod
def to_jpeg(pres, output_file_name):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/vi/aspose.slides/presentation) | Bản trình bày đầu vào. |
| output_file_name | **str** | Tên tệp đầu ra. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, image_size) {#presentation-str-asposepydrawingsize}
Chuyển đổi bản trình bày đầu vào thành một tập hợp các hình ảnh định dạng JPEG.  
Nếu tên tệp đầu ra được cung cấp dưới dạng "myPath/myFilename.jpeg", 
kết quả sẽ được lưu dưới dạng một tập hợp các tệp "myPath/myFilename_N.jpeg", trong đó N là số slide.


```python
@staticmethod
def to_jpeg(pres, output_file_name, image_size):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/vi/aspose.slides/presentation) | Bản trình bày đầu vào |
| output_file_name | **str** | Tên tệp đầu ra. |
| image_size | **aspose.slides.Size** | Kích thước của mỗi hình ảnh được tạo. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
Chuyển đổi bản trình bày đầu vào thành một tập hợp các hình ảnh định dạng JPEG.  
Nếu tên tệp đầu ra được cung cấp dưới dạng "myPath/myFilename.jpeg", 
kết quả sẽ được lưu dưới dạng một tập hợp các tệp "myPath/myFilename_N.jpeg", trong đó N là số slide.


```python
@staticmethod
def to_jpeg(pres, output_file_name, scale, options):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/vi/aspose.slides/presentation) | Bản trình bày đầu vào. |
| output_file_name | **str** | Tên tệp đầu ra. |
| scale | **float** | Hệ số phóng đại được áp dụng cho các hình ảnh đầu ra so với kích thước slide gốc. |
| options | [`IRenderingOptions`](/slides/python-net/vi/aspose.slides.export/irenderingoptions) | Các tùy chọn render. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### Xem thêm
* lớp [`Convert`](/slides/python-net/vi/aspose.slides.lowcode/convert)
* lớp [`IRenderingOptions`](/slides/python-net/vi/aspose.slides.export/irenderingoptions)
* lớp [`Presentation`](/slides/python-net/vi/aspose.slides/presentation)
* module [`aspose.slides.lowcode`](/slides/python-net/vi/aspose.slides.lowcode)
* thư viện [`Aspose.Slides`](/slides/python-net)
---
title: compress_image method
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/picturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
Nén hình ảnh bằng cách giảm kích thước dựa trên kích thước hình dạng và độ phân giải được chỉ định. Tùy chọn, nó cũng có thể xóa các khu vực đã cắt.

### Trả về

Một **bool** cho biết liệu hình ảnh có được nén thành công hay không. Trả về **True** nếu hình ảnh đã được thay đổi kích thước hoặc cắt, nếu không **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Nếu true, phương thức sẽ loại bỏ các khu vực đã cắt của hình ảnh, có thể giảm kích thước hơn nữa. |
| resolution | [`PicturesCompression`](/slides/python-net/vi/aspose.slides.export/picturescompression) | Độ phân giải mục tiêu cho việc nén, được chỉ định dưới dạng một giá trị của enum [`PicturesCompression`](/slides/python-net/vi/aspose.slides.export/picturescompression). |

### Ghi chú

Phương thức này thay đổi kích thước và độ phân giải của hình ảnh tương tự như tính năng "Picture Format -> Compress Pictures" của PowerPoint.

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Bị ném khi độ phân giải không phải là một giá trị hợp lệ. |


## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
Nén hình ảnh bằng cách giảm kích thước dựa trên kích thước hình dạng và độ phân giải được chỉ định. Tùy chọn, nó cũng có thể xóa các khu vực đã cắt.

### Trả về

Một **bool** cho biết liệu hình ảnh có được nén thành công hay không. Trả về **True** nếu hình ảnh đã được thay đổi kích thước hoặc cắt, nếu không **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Nếu true, phương thức sẽ loại bỏ các khu vực đã cắt của hình ảnh, có thể giảm kích thước hơn nữa. |
| resolution | **float** | Độ phân giải mục tiêu tính bằng DPI. Giá trị này phải dương và xác định cách hình ảnh sẽ được thay đổi kích thước. |

### Ghi chú

Phương thức này thay đổi kích thước và độ phân giải của hình ảnh tương tự như tính năng "Picture Format -> Compress Pictures" của PowerPoint.

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Bị ném khi độ phân giải không phải là một giá trị dương. |



### Xem thêm
* lớp [`PictureFillFormat`](/slides/python-net/vi/aspose.slides/picturefillformat)
* enumeration [`PicturesCompression`](/slides/python-net/vi/aspose.slides.export/picturescompression)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
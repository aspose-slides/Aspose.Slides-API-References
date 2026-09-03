---
title: get_image method
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides/iparagraph/get_image/
weight: 10
---
## get_image {#}
Trả về một hình ảnh của đoạn văn.

### Giá trị trả về

Một hình ảnh chứa đoạn văn đã được hiển thị, hoặc **None**
             nếu đoạn văn không thể tìm thấy trong bộ sưu tập cha, không có
             giới hạn hiển thị hợp lệ, hoặc xảy ra lỗi khi hiển thị hình ảnh.



```python
def get_image(self):
    ...
```


## get_image {#float-float}
Trả về một hình ảnh của đoạn văn với tỷ lệ đã chỉ định.

### Giá trị trả về

Một hình ảnh chứa đoạn văn đã được hiển thị, hoặc **None**
             nếu đoạn văn không thể tìm thấy trong bộ sưu tập cha, không có
             giới hạn hiển thị hợp lệ, hoặc xảy ra lỗi khi hiển thị hình ảnh.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| scale_x | **float** | Hệ số tỷ lệ ngang áp dụng cho hình ảnh đoạn văn. |
| scale_y | **float** | Hệ số tỷ lệ dọc áp dụng cho hình ảnh đoạn văn. |



### Xem thêm
* lớp [`IImage`](/slides/python-net/vi/aspose.slides/iimage)
* lớp [`IParagraph`](/slides/python-net/vi/aspose.slides/iparagraph)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
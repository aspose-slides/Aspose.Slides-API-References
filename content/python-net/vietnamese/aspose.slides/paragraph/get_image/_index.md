---
title: get_image method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/paragraph/get_image/
weight: 20
---
## get_image {#}
Trả về một hình ảnh của đoạn văn.

### Trả về

Một hình ảnh chứa đoạn văn đã được render, hoặc **None** nếu đoạn văn không thể tìm thấy trong bộ sưu tập cha, không có giới hạn render hợp lệ, hoặc xảy ra lỗi khi render hình ảnh.



```python
def get_image(self):
    ...
```



## get_image {#float-float}
Trả về một hình ảnh của đoạn văn với tỉ lệ đã chỉ định.

### Trả về

Một hình ảnh chứa đoạn văn đã được render, hoặc **None** nếu đoạn văn không thể tìm thấy trong bộ sưu tập cha, không có giới hạn render hợp lệ, hoặc xảy ra lỗi khi render hình ảnh.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| scale_x | **float** | Hệ số tỷ lệ ngang được áp dụng cho hình ảnh đoạn văn. |
| scale_y | **float** | Hệ số tỷ lệ dọc được áp dụng cho hình ảnh đoạn văn. |



### Xem thêm
* lớp [`IImage`](/slides/python-net/vi/aspose.slides/iimage)
* lớp [`Paragraph`](/slides/python-net/vi/aspose.slides/paragraph)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
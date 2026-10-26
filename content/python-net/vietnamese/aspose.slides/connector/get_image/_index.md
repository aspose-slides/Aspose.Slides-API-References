---
title: get_image method
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/connector/get_image/
weight: 50
---
## get_image(self) {#}
Trả về hình thu nhỏ của shape.
            Kiểu giới hạn hình thu nhỏ ShapeThumbnailBounds.Shape được sử dụng mặc định.

### Trả về

Hình thu nhỏ của shape.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Trả về hình thu nhỏ của shape.

### Trả về

Hình thu nhỏ của shape hoặc None trong trường hợp ShapeThumbnailBounds.Appearance được sử dụng và shape không có phần tử hiển thị.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/vi/aspose.slides/shapethumbnailbounds) | Loại giới hạn hình thu nhỏ. |
| scale_x | **float** | Tỷ lệ X |
| scale_y | **float** | Tỷ lệ Y |



### Xem thêm
* lớp [`Connector`](/slides/python-net/vi/aspose.slides/connector)
* lớp [`IImage`](/slides/python-net/vi/aspose.slides/iimage)
* liệt kê [`ShapeThumbnailBounds`](/slides/python-net/vi/aspose.slides/shapethumbnailbounds)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
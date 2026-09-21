---
title: get_image method
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides/autoshape/get_image/
weight: 60
---
## get_image(self) {#}
Trả về hình thu nhỏ của shape.  
Kiểu giới hạn hình thu nhỏ ShapeThumbnailBounds.Shape được sử dụng theo mặc định.

### Trả về

Hình thu nhỏ của shape.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Trả về hình thu nhỏ của shape.

### Trả về

Hình thu nhỏ của shape hoặc None trong trường hợp ShapeThumbnailBounds.Appearance được sử dụng và một shape không có các phần tử hiển thị.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/vi/aspose.slides/shapethumbnailbounds) | Kiểu giới hạn hình thu nhỏ Shape. |
| scale_x | **float** | tỷ lệ X |
| scale_y | **float** | tỷ lệ Y |



### Xem thêm
* lớp [`AutoShape`](/slides/python-net/vi/aspose.slides/autoshape)
* lớp [`IImage`](/slides/python-net/vi/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/vi/aspose.slides/shapethumbnailbounds)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
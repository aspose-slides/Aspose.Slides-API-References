---
title: get_image method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.smartart/smartart/get_image/
weight: 30
---
## get_image(self) {#}
Trả về hình thu nhỏ của shape.  
ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

### Trả về

Shape thumbnail.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Trả về hình thu nhỏ của shape.

### Trả về

Shape thumbnail hoặc None trong trường hợp ShapeThumbnailBounds.Appearance được sử dụng và shape không có các phần tử hiển thị.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/vi/aspose.slides/shapethumbnailbounds) | Kiểu giới hạn hình thu nhỏ của Shape. |
| scale_x | **float** | tỷ lệ X |
| scale_y | **float** | tỷ lệ Y |



### Xem thêm
* lớp [`IImage`](/slides/python-net/vi/aspose.slides/iimage)
* liệt kê [`ShapeThumbnailBounds`](/slides/python-net/vi/aspose.slides/shapethumbnailbounds)
* lớp [`SmartArt`](/slides/python-net/vi/aspose.slides.smartart/smartart)
* mô-đun [`aspose.slides.smartart`](/slides/python-net/vi/aspose.slides.smartart)
* thư viện [`Aspose.Slides`](/slides/python-net)
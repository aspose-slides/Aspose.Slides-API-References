---
title: get_image method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/shape/get_image/
weight: 30
---
## get_image(self) {#}
Trả về hình thu nhỏ của shape.
ShapeThumbnailBounds.Shape shape thumbnail bounds type được sử dụng theo mặc định.

### Trả về

Shape hình thu nhỏ.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Trả về hình thu nhỏ của shape.

### Trả về

Shape thumbnail hoặc None trong trường hợp khi ShapeThumbnailBounds.Appearance được sử dụng và một shape không có các phần tử hiển thị.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/vi/aspose.slides/shapethumbnailbounds) | Shape hình thu nhỏ bounds type. |
| scale_x | **float** | tỷ lệ X |
| scale_y | **float** | tỷ lệ Y |



### Xem thêm
* lớp [`IImage`](/slides/python-net/vi/aspose.slides/iimage)
* lớp [`Shape`](/slides/python-net/vi/aspose.slides/shape)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/vi/aspose.slides/shapethumbnailbounds)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
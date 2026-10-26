---
title: get_image method
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/sectionzoomframe/get_image/
weight: 30
---
## get_image(self) {#}
Trả về hình thu nhỏ của shape.
            Loại giới hạn hình thu nhỏ của shape ShapeThumbnailBounds.Shape được sử dụng mặc định.

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
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/vi/aspose.slides/shapethumbnailbounds) | Loại giới hạn hình thu nhỏ của shape. |
| scale_x | **float** | Tỷ lệ X |
| scale_y | **float** | Tỷ lệ Y |



### Xem thêm
* lớp [`IImage`](/slides/python-net/vi/aspose.slides/iimage)
* lớp [`SectionZoomFrame`](/slides/python-net/vi/aspose.slides/sectionzoomframe)
* liệt kê [`ShapeThumbnailBounds`](/slides/python-net/vi/aspose.slides/shapethumbnailbounds)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
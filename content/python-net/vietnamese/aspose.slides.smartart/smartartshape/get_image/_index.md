---
title: get_image method
second_title: Aspose.Slides cho Python qua .NET Tham khảo API
description: 
type: docs
url: /vi/aspose.slides.smartart/smartartshape/get_image/
weight: 50
---
## get_image(self) {#}
Trả về hình thu nhỏ của shape.
Kiểu giới hạn shape thumbnail ShapeThumbnailBounds.Shape được sử dụng theo mặc định.

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
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/vi/aspose.slides/shapethumbnailbounds) | Kiểu giới hạn shape thumbnail. |
| scale_x | **float** | tỷ lệ X |
| scale_y | **float** | tỷ lệ Y |

### Xem thêm
* lớp [`IImage`](/slides/python-net/vi/aspose.slides/iimage)
* liệt kê [`ShapeThumbnailBounds`](/slides/python-net/vi/aspose.slides/shapethumbnailbounds)
* lớp [`SmartArtShape`](/slides/python-net/vi/aspose.slides.smartart/smartartshape)
* mô-đun [`aspose.slides.smartart`](/slides/python-net/vi/aspose.slides.smartart)
* library [`Aspose.Slides`](/slides/python-net)
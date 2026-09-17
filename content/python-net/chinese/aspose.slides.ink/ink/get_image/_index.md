---
title: get_image method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.ink/ink/get_image/
weight: 30
---
## get_image(self) {#}
Returns shape thumbnail.
            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

### 返回

形状缩略图.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Returns shape thumbnail.

### 返回

当使用 ShapeThumbnailBounds.Appearance 且形状没有可见元素时，返回形状缩略图或 None.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/zh/aspose.slides/shapethumbnailbounds) | 形状缩略图边界类型。 |
| scale_x | **float** | X 缩放 |
| scale_y | **float** | Y 缩放 |



### 另见
* 类 [`IImage`](/slides/python-net/zh/aspose.slides/iimage)
* 类 [`Ink`](/slides/python-net/zh/aspose.slides.ink/ink)
* 枚举 [`ShapeThumbnailBounds`](/slides/python-net/zh/aspose.slides/shapethumbnailbounds)
* 模块 [`aspose.slides.ink`](/slides/python-net/zh/aspose.slides.ink)
* 库 [`Aspose.Slides`](/slides/python-net)
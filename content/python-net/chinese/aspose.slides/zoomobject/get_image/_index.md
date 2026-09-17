---
title: get_image method
second_title: Aspose.Slides 用于 Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/zoomobject/get_image/
weight: 30
---
## get_image(self) {#}
返回 Shape 缩略图。
默认使用 ShapeThumbnailBounds.Shape 形状缩略图边界类型。

### 返回

Shape 缩略图。

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
返回 Shape 缩略图。

### 返回

在使用 ShapeThumbnailBounds.Appearance 且 shape 没有可见元素的情况下，返回 Shape 缩略图 或 None。

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/zh/aspose.slides/shapethumbnailbounds) | Shape 缩略图边界类型。 |
| scale_x | **float** | X 缩放 |
| scale_y | **float** | Y 缩放 |

### 另见
* 类 [`IImage`](/slides/python-net/zh/aspose.slides/iimage)
* 枚举 [`ShapeThumbnailBounds`](/slides/python-net/zh/aspose.slides/shapethumbnailbounds)
* 类 [`ZoomObject`](/slides/python-net/zh/aspose.slides/zoomobject)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)
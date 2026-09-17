---
title: get_image method
second_title: Aspose.Slides 的 Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/table/get_image/
weight: 30
---
## get_image(self) {#}
返回形状缩略图。默认使用 ShapeThumbnailBounds.Shape shape thumbnail bounds type。

### 返回

Shape thumbnail.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
返回形状缩略图。

### 返回

Shape thumbnail 或 None（当使用 ShapeThumbnailBounds.Appearance 且形状没有可见元素时）。

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/zh/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds 类型。 |
| scale_x | **float** | X 缩放 |
| scale_y | **float** | Y 缩放 |

### 另请参见
* 类 [`IImage`](/slides/python-net/zh/aspose.slides/iimage)
* 枚举 [`ShapeThumbnailBounds`](/slides/python-net/zh/aspose.slides/shapethumbnailbounds)
* 类 [`Table`](/slides/python-net/zh/aspose.slides/table)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)
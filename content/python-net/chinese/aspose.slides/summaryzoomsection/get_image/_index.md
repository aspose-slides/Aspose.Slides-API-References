---
title: get_image method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/summaryzoomsection/get_image/
weight: 30
---
## get_image(self) {#}
返回形状缩略图。
默认使用 ShapeThumbnailBounds.Shape 形状缩略图边界类型。

### Returns

形状缩略图。

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
返回形状缩略图。

### Returns

如果使用 ShapeThumbnailBounds.Appearance 并且形状没有可见元素，则返回形状缩略图或 None。

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/zh/aspose.slides/shapethumbnailbounds) | 形状缩略图边界类型。 |
| scale_x | **float** | X 缩放 |
| scale_y | **float** | Y 缩放 |

### See Also
* 类 [`IImage`](/slides/python-net/zh/aspose.slides/iimage)
* 枚举 [`ShapeThumbnailBounds`](/slides/python-net/zh/aspose.slides/shapethumbnailbounds)
* 类 [`SummaryZoomSection`](/slides/python-net/zh/aspose.slides/summaryzoomsection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)
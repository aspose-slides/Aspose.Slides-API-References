---
title: set_size method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/islidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
设置幻灯片大小（通过类型），并缩放现有内容。

```python
def set_size(self, type, scale_type):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/zh/aspose.slides/slidesizetype) | 要应用的预定义幻灯片大小。 |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/zh/aspose.slides/slidesizescaletype) | 要使用的内容缩放模式。 |

### 备注

将除 [`SlideSizeType.CUSTOM`](/slides/python-net/zh/aspose.slides/slidesizetype/CUSTOM) 之外的任何值分配给 [`ISlideSize.size`](/slides/python-net/zh/aspose.slides/islidesize/size) 时，会根据所选类型进行调整，同时保留 [`ISlideSize.orientation`](/slides/python-net/zh/aspose.slides/islidesize/orientation)。

## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
显式设置幻灯片尺寸，并缩放现有内容。

```python
def set_size(self, width, height, scale_type):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| width | **float** | 新的幻灯片宽度（单位：点）。 |
| height | **float** | 新的幻灯片高度（单位：点）。 |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/zh/aspose.slides/slidesizescaletype) | 要使用的内容缩放模式。 |

### 备注

此操作将 [`ISlideSize.type`](/slides/python-net/zh/aspose.slides/islidesize/type) 属性重置为 [`SlideSizeType.CUSTOM`](/slides/python-net/zh/aspose.slides/slidesizetype/CUSTOM)，并设置 [`ISlideSize.orientation`](/slides/python-net/zh/aspose.slides/islidesize/orientation)。

### 另见
* 类 [`ISlideSize`](/slides/python-net/zh/aspose.slides/islidesize)
* 枚举 [`SlideSizeScaleType`](/slides/python-net/zh/aspose.slides/slidesizescaletype)
* 枚举 [`SlideSizeType`](/slides/python-net/zh/aspose.slides/slidesizetype)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)
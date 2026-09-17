---
title: set_size method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/slidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
通过类型设置幻灯片尺寸并缩放现有内容。

```python
def set_size(self, type, scale_type):
    ...
```

| 参数 | 类型 | 说明 |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/zh/aspose.slides/slidesizetype) | 要应用的预定义幻灯片尺寸。 |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/zh/aspose.slides/slidesizescaletype) | 要使用的内容缩放模式。 |

### 备注
分配除 [`SlideSizeType.CUSTOM`](/slides/python-net/zh/aspose.slides/slidesizetype/CUSTOM) 之外的任何值会根据所选类型调整 [`SlideSize.size`](/slides/python-net/zh/aspose.slides/slidesize/size)
            ，同时保留 [`SlideSize.orientation`](/slides/python-net/zh/aspose.slides/slidesize/orientation)。

## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
显式设置幻灯片尺寸并缩放现有内容。

```python
def set_size(self, width, height, scale_type):
    ...
```

| 参数 | 类型 | 说明 |
| :- | :- | :- |
| width | **float** | 新幻灯片宽度，以点为单位。 |
| height | **float** | 新幻灯片高度，以点为单位。 |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/zh/aspose.slides/slidesizescaletype) | 要使用的内容缩放模式。 |

### 备注
这会将 [`SlideSize.type`](/slides/python-net/zh/aspose.slides/slidesize/type) 属性重置为 [`SlideSizeType.CUSTOM`](/slides/python-net/zh/aspose.slides/slidesizetype/CUSTOM)
            并设置 [`SlideSize.orientation`](/slides/python-net/zh/aspose.slides/slidesize/orientation)。

### 另请参阅
* 类 [`SlideSize`](/slides/python-net/zh/aspose.slides/slidesize)
* 枚举 [`SlideSizeScaleType`](/slides/python-net/zh/aspose.slides/slidesizescaletype)
* 枚举 [`SlideSizeType`](/slides/python-net/zh/aspose.slides/slidesizetype)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)
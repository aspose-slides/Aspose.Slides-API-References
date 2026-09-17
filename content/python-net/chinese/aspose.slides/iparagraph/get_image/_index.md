---
title: get_image method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/iparagraph/get_image/
weight: 10
---
## get_image(self) {#}
返回段落的图像。

### 返回

包含已渲染段落的图像，或 **None**
             如果在其父集合中找不到段落，或者没有有效的渲染边界，或在渲染图像时发生错误。

```python
def get_image(self):
    ...
```

## get_image(self, scale_x, scale_y) {#float-float}
返回指定比例的段落图像。

### 返回

包含已渲染段落的图像，或 **None**
             如果在其父集合中找不到段落，或者没有有效的渲染边界，或在渲染图像时发生错误。

```python
def get_image(self, scale_x, scale_y):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| scale_x | **float** | 应用于段落图像的水平缩放因子。 |
| scale_y | **float** | 应用于段落图像的垂直缩放因子。 |

### 另见
* 类 [`IImage`](/slides/python-net/zh/aspose.slides/iimage)
* 类 [`IParagraph`](/slides/python-net/zh/aspose.slides/iparagraph)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)
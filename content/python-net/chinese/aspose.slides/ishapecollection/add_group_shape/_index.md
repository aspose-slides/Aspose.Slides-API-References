---
title: add_group_shape method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ishapecollection/add_group_shape/
weight: 80
---
## add_group_shape(self) {#}
创建一个新的空白组形状，并将其添加到形状集合的末尾。组的框架会自动调整以适应添加的任何形状。

### 返回

新创建的 [`IGroupShape`](/slides/python-net/zh/aspose.slides/igroupshape)。

```python
def add_group_shape(self):
    ...
```

## add_group_shape(self, svg_image, x, y, width, height) {#isvgimage-float-float-float-float}
创建一个新的组形状，将指定的 SVG 图像转换为单独的形状，并将生成的组添加到形状集合的末尾。

### 返回

新创建的 [`IGroupShape`](/slides/python-net/zh/aspose.slides/igroupshape)。

```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/zh/aspose.slides/isvgimage) | [`ISvgImage`](/slides/python-net/zh/aspose.slides/isvgimage) 包含要转换为形状的矢量内容。 |
| x | **float** | 组框架的 x 坐标，单位为点。 |
| y | **float** | 组框架的 y 坐标，单位为点。 |
| width | **float** | 组框架的宽度，单位为点。 |
| height | **float** | 组框架的高度，单位为点。 |

### 参见
* 类 [`IGroupShape`](/slides/python-net/zh/aspose.slides/igroupshape)
* 类 [`IShapeCollection`](/slides/python-net/zh/aspose.slides/ishapecollection)
* 类 [`ISvgImage`](/slides/python-net/zh/aspose.slides/isvgimage)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)
---
title: add_group_shape method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/shapecollection/add_group_shape/
weight: 80
---
## add_group_shape(self) {#}
创建一个新的空白组形状并将其添加到形状集合的末尾。
            组的框架会自动调整以适应添加的任何形状。

### 返回

新创建的 [`IGroupShape`](/slides/python-net/zh/aspose.slides/igroupshape)。

```python
def add_group_shape(self):
    ...
```

## add_group_shape(self, svg_image, x, y, width, height) {#isvgimage-float-float-float-float}
创建一个新的组形状，将指定的 SVG 图像转换为单个形状，
            并将生成的组添加到形状集合的末尾。

### 返回

新创建的 [`IGroupShape`](/slides/python-net/zh/aspose.slides/igroupshape)。

```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/zh/aspose.slides/isvgimage) | 包含要转换为形状的矢量内容的 [`ISvgImage`](/slides/python-net/zh/aspose.slides/isvgimage)。 |
| x | **float** | 组框架的 x 坐标，以点为单位。 |
| y | **float** | 组框架的 y 坐标，以点为单位。 |
| width | **float** | 组框架的宽度，以点为单位。 |
| height | **float** | 组框架的高度，以点为单位。 |

### 另见
* class [`IGroupShape`](/slides/python-net/zh/aspose.slides/igroupshape)
* class [`ISvgImage`](/slides/python-net/zh/aspose.slides/isvgimage)
* class [`ShapeCollection`](/slides/python-net/zh/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
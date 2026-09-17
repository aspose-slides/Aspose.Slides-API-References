---
title: add_chart method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ishapecollection/add_chart/
weight: 50
---
## add_chart(self, type, x, y, width, height) {#asposeslideschartscharttype-float-float-float-float}
创建一个新图表，使用示例系列数据和设置进行初始化，并将其添加到形状集合的末尾。

### 返回

新创建的[`IChart`](/slides/python-net/zh/aspose.slides.charts/ichart)。

```python
def add_chart(self, type, x, y, width, height):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/zh/aspose.slides.charts/charttype) | 要添加的图表类型。 |
| x | **float** | 新图表的 x 坐标，单位为点。 |
| y | **float** | 新图表的 y 坐标，单位为点。 |
| width | **float** | 图表的宽度，单位为点。 |
| height | **float** | 图表的高度，单位为点。 |

## add_chart(self, type, x, y, width, height, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-bool}
创建一个新图表，使用示例系列数据和设置进行初始化，并将其添加到形状集合的末尾。

### 返回

新创建的[`IChart`](/slides/python-net/zh/aspose.slides.charts/ichart)。

```python
def add_chart(self, type, x, y, width, height, init_with_sample):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/zh/aspose.slides.charts/charttype) | 要添加的图表类型。 |
| x | **float** | 新图表的 x 坐标，单位为点。 |
| y | **float** | 新图表的 y 坐标，单位为点。 |
| width | **float** | 图表的宽度，单位为点。 |
| height | **float** | 图表的高度，单位为点。 |
| init_with_sample | **bool** | True表示使用示例系列数据和设置初始化新图表； <br/><br/>            false表示创建没有系列且仅有最小设置的图表，这将加快创建速度。 |

### 另见
* 枚举 [`ChartType`](/slides/python-net/zh/aspose.slides.charts/charttype)
* 类 [`IChart`](/slides/python-net/zh/aspose.slides.charts/ichart)
* 类 [`IShapeCollection`](/slides/python-net/zh/aspose.slides/ishapecollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)
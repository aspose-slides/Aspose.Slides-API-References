---
title: insert_chart method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/shapecollection/insert_chart/
weight: 240
---
## insert_chart(self, type, x, y, width, height, index) {#asposeslideschartscharttype-float-float-float-float-int}
创建一个新图表，使用示例系列数据和设置进行初始化，并将其插入到指定索引的形状集合中。

### Returns

新创建的[`IChart`](/slides/python-net/zh/aspose.slides.charts/ichart)。



```python
def insert_chart(self, type, x, y, width, height, index):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/zh/aspose.slides.charts/charttype) | 要创建的图表类型。 |
| x | **float** | 新图表的 x 坐标（单位：点）。 |
| y | **float** | 新图表的 y 坐标（单位：点）。 |
| width | **float** | 新图表的宽度（单位：点）。 |
| height | **float** | 新图表的高度（单位：点）。 |
| index | **int** | 在形状集合中插入新图表的基于零的索引。 |


## insert_chart(self, type, x, y, width, height, index, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-int-bool}
创建一个新图表，使用示例系列数据和设置进行初始化，并将其插入到指定索引的形状集合中。

### Returns

新创建的[`IChart`](/slides/python-net/zh/aspose.slides.charts/ichart)。



```python
def insert_chart(self, type, x, y, width, height, index, init_with_sample):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/zh/aspose.slides.charts/charttype) | 要创建的图表类型。 |
| x | **float** | 新图表的 x 坐标（单位：点）。 |
| y | **float** | 新图表的 y 坐标（单位：点）。 |
| width | **float** | 新图表的宽度（单位：点）。 |
| height | **float** | 新图表的高度（单位：点）。 |
| index | **int** | 在形状集合中插入新图表的基于零的索引。 |
| init_with_sample | **bool** | True 表示使用示例系列数据和设置初始化新图表；false 表示创建没有系列且仅包含最少设置的图表，这会加快创建速度。 |



### See Also
* 枚举 [`ChartType`](/slides/python-net/zh/aspose.slides.charts/charttype)
* 类 [`IChart`](/slides/python-net/zh/aspose.slides.charts/ichart)
* 类 [`ShapeCollection`](/slides/python-net/zh/aspose.slides/shapecollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)
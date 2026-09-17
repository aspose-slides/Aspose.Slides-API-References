---
title: IChartSeriesGroupCollection class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/ichartseriesgroupcollection/
---
## IChartSeriesGroupCollection 类

表示可组合系列的组集合。

IChartSeriesGroupCollection 类型公开以下成员：

按索引获取系列组。

## 索引器

| 名称 | 描述 |
| :- | :- |
| [`[index]`](/slides/python-net/zh/aspose.slides.charts/ichartseriesgroupcollection/__getitem__/) |  |


### 备注

1) 每个系列组包含具有可组合类型的系列。可组合系列类型的组由 **CombinableSeriesTypesGroup** 枚举定义并描述。  
   同时，每个系列组中的系列只能绘制在主坐标轴或副坐标轴上（同一组中不会出现两者同时绘制的情况）。  
   因此，系列分组的原则是上述类型组的分组以及主/副坐标轴的绘制类型分组。

2) 系列组包含一些对组内所有系列通用的系列属性（“系列组属性”）。  
   **ChartSeriesGroup** 类中的“系列组属性”是可读写的。  
   每个“系列组属性”在 **ChartSeries** 类中可以有只读的投影。

### 另见
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)
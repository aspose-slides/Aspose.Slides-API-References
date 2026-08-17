---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides for Java API 参考
description: 表示可组合系列组的集合。
type: docs
url: /zh/com.aspose.slides/ichartseriesgroupcollection/
---
**所有实现的接口：**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

表示可组合系列组的集合。

--------------------

1) 每个系列组包含具有可组合类型的系列。使用 **CombinableSeriesTypesGroup** 枚举定义并描述可组合系列类型的组。另且每个系列组包含绘制在主坐标轴或次坐标轴上的系列（同一组中不同时出现两者）。因此，系列分组的原则是按照上述类型组以及主/次坐标轴绘制类型进行分组。  
2) 系列组包含一些对组内每个系列通用的系列属性（“series group properties”）。**ChartSeriesGroup** 类中的 “Series group properties” 为可读写。每个 “Series group properties” 在 **ChartSeries** 类中可以有只读的投影。

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | 通过系列获取系列组。 |
| [get_Item(int index)](#get-Item-int-) | 通过索引获取系列组。 |
### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```


通过系列获取系列组。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ofSeries | [IChartSeries](../../com.aspose.slides/ichartseries) |  |

**返回:**  
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeriesGroup get_Item(int index)
```


通过索引获取系列组。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回:**  
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
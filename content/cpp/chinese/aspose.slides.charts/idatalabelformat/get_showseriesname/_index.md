---
title: get_ShowSeriesName()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个布尔值，以指示图表中数据标签的系列名称显示行为。True 表示显示系列名称。False 表示隐藏。读取 bool.
type: docs
weight: 170
url: /zh/aspose.slides.charts/idatalabelformat/get_showseriesname/
---
## IDataLabelFormat::get_ShowSeriesName() 方法

返回一个布尔值，用于指示图表中数据标签的系列名称显示行为。True 表示显示系列名称。False 表示隐藏。读取 **bool**。

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowSeriesName()=0
```

## 备注

如果此 [DataLabelFormat](../../datalabelformat/) 对象的父对象是一个 [DataLabelCollection](../../datalabelcollection/) 数据标签集合，则此属性获取或设置 [DataLabelCollection](../../datalabelcollection/) 集合中新数据标签的 ShowSeriesName 属性的默认值。使用该值设置此属性还会将此值设置为 [DataLabelCollection](../../datalabelcollection/) 集合中所有数据标签的 ShowSeriesName 属性（即 "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" 导致所有 DataLabels[i].ShowSeriesName 等于 val）。

## 另见

* 类 [IDataLabelFormat](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)
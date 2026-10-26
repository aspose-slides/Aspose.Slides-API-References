---
title: set_ShowSeriesName()
second_title: Aspose.Slides C++ API 参考
description: 设置一个 Boolean，以指示图表上数据标签的系列名称显示行为。True 表示显示系列名称。False 表示隐藏。写入 bool.
type: docs
weight: 183
url: /zh/aspose.slides.charts/idatalabelformat/set_showseriesname/
---
## IDataLabelFormat::set_ShowSeriesName(bool) 方法

设置一个 Boolean，以指示图表上数据标签的系列名称显示行为。True 表示显示系列名称。False 表示隐藏。写入 **bool**。

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowSeriesName(bool value)=0
```

## 备注

如果此 [DataLabelFormat](../../datalabelformat/) 对象的父级是 [DataLabelCollection](../../datalabelcollection/) 数据标签集合，则该属性获取或设置 [DataLabelCollection](../../datalabelcollection/) 集合中新数据标签的 ShowSeriesName 属性的默认值。使用该属性赋值时，也会将此值设置为 [DataLabelCollection](../../datalabelcollection/) 集合中所有数据标签的 ShowSeriesName 属性（即 "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" 导致所有 DataLabels[i].ShowSeriesName 等于 val）。

## 另见

* 类 [IDataLabelFormat](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)
---
title: set_ShowPercentage()
second_title: Aspose.Slides for C++ API 参考
description: 表示指定图表的数据标签百分比值的显示行为。True 表示显示百分比值。False 表示隐藏。写入 bool.
type: docs
weight: 209
url: /zh/aspose.slides.charts/idatalabelformat/set_showpercentage/
---
## IDataLabelFormat::set_ShowPercentage(bool) 方法

表示指定图表的数据标签百分比值的显示行为。True 表示显示百分比值。False 表示隐藏。写入 **bool**。

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowPercentage(bool value)=0
```

## 备注

如果此 [DataLabelFormat](../../datalabelformat/) 对象的父级是 [DataLabelCollection](../../datalabelcollection/) 数据标签集合，则此属性获取或设置 [DataLabelCollection](../../datalabelcollection/) 集合中新数据标签的 ShowPercentage 属性的默认值。使用该值设置此属性时，也会将该值设置为 [DataLabelCollection](../../datalabelcollection/) 集合中所有数据标签的 ShowPercentage 属性（即 "DataLabels.DefaultDataLabelFormat.ShowPercentage = val;" 导致所有 DataLabels[i].ShowPercentage 等于 val）。

## 另见

* 类 [IDataLabelFormat](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)
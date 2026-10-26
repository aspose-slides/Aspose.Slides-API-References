---
title: get_ShowPercentage()
second_title: Aspose.Slides C++ API 参考
description: 表示指定图表的数据标签百分比值的显示行为。True 显示百分比值。False 隐藏。读取 bool。
type: docs
weight: 196
url: /zh/aspose.slides.charts/idatalabelformat/get_showpercentage/
---
## IDataLabelFormat::get_ShowPercentage() 方法

表示指定图表的数据标签百分比值的显示行为。True 显示百分比值。False 隐藏。读取 **bool**。

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowPercentage()=0
```

## 备注

如果此 [DataLabelFormat](../../datalabelformat/) 对象的父对象是 [DataLabelCollection](../../datalabelcollection/) 数据标签集合，则此属性获取或设置 [DataLabelCollection](../../datalabelcollection/) 集合中新数据标签的 ShowPercentage 属性的默认值。使用该值设置此属性也会将此值设置为 [DataLabelCollection](../../datalabelcollection/) 集合中所有数据标签的 ShowPercentage 属性（即 "DataLabels.DefaultDataLabelFormat.ShowPercentage = val;" 会导致所有 DataLabels[i].ShowPercentage 等于 val）。

## 另请参阅

* 类 [IDataLabelFormat](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)
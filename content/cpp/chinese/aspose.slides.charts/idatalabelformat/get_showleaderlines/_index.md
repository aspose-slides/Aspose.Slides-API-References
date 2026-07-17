---
title: get_ShowLeaderLines()
second_title: Aspose.Slides C++ API 参考
description: 表示指定图表的数据标签引导线的显示行为。True 显示引导线。False 隐藏。读取 bool。
type: docs
weight: 248
url: /zh/aspose.slides.charts/idatalabelformat/get_showleaderlines/
---
## IDataLabelFormat::get_ShowLeaderLines() 方法

表示指定图表的数据标签引导线的显示行为。True 显示引导线。False 隐藏。读取 **bool**。

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowLeaderLines()=0
```

## 备注

如果此 [DataLabelFormat](../../datalabelformat/) 对象的父对象是 [DataLabelCollection](../../datalabelcollection/) 数据标签集合，则此属性获取或设置 [DataLabelCollection](../../datalabelcollection/) 集合中新数据标签的 ShowLeaderLines 属性的默认值。使用该属性设置值时，也会将此值设置为 [DataLabelCollection](../../datalabelcollection/) 集合中所有数据标签的 ShowLeaderLines 属性（即 "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" 导致所有 DataLabels[i].ShowLeaderLines 等于 val）。

## 另请参阅

* 类 [IDataLabelFormat](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)
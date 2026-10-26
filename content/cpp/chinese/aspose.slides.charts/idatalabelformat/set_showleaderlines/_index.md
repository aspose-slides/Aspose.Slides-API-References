---
title: set_ShowLeaderLines()
second_title: Aspose.Slides for C++ API 参考
description: 表示指定图表的数据标签引导线的显示行为。True 显示引导线。False 隐藏。写入 bool.
type: docs
weight: 261
url: /zh/aspose.slides.charts/idatalabelformat/set_showleaderlines/
---
## IDataLabelFormat::set_ShowLeaderLines(bool) 方法


表示指定图表的数据标签引导线的显示行为。True 显示引导线。False 隐藏。写入 **bool**。

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowLeaderLines(bool value)=0
```

## 备注


如果此 [DataLabelFormat](../../datalabelformat/) 对象的父对象是 [DataLabelCollection](../../datalabelcollection/) 数据标签集合，则此属性获取或设置 [DataLabelCollection](../../datalabelcollection/) 集合中新数据标签的 ShowLeaderLines 属性的默认值。将此属性设置为某个值也会将该值设置为 [DataLabelCollection](../../datalabelcollection/) 集合中所有数据标签的 ShowLeaderLines 属性（即 \"DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;\" 导致所有 DataLabels[i].ShowLeaderLines 等于 val）。
## 另见

* 类 [IDataLabelFormat](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)
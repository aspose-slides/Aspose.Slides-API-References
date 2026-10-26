---
title: get_ShowLeaderLines()
second_title: Aspose.Slides C++ API 参考
description: 表示指定图表的数据标签引导线的显示行为。True 表示显示引导线，False 表示隐藏。只读 bool。
type: docs
weight: 248
url: /zh/aspose.slides.charts/datalabelformat/get_showleaderlines/
---
## DataLabelFormat::get_ShowLeaderLines() 方法

表示指定图表的数据标签引导线显示行为。True 表示显示引导线。False 表示隐藏。读取 **bool**.

```cpp
bool Aspose::Slides::Charts::DataLabelFormat::get_ShowLeaderLines() override
```

## 备注

如果此 [DataLabelFormat](../) 对象的父级是一个 [DataLabelCollection](../../datalabelcollection/) 数据标签集合，则此属性获取或设置 [DataLabelCollection](../../datalabelcollection/) 集合中新数据标签的 ShowLeaderLines 属性的默认值。使用该值设置此属性还会将此值设置为 [DataLabelCollection](../../datalabelcollection/) 集合中所有数据标签的 ShowLeaderLines 属性（即 "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" 会导致所有 DataLabels[i].ShowLeaderLines 等于 val）。

## 另请参阅

* 类 [DataLabelFormat](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)
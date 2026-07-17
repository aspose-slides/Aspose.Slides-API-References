---
title: set_ShowLegendKey()
second_title: Aspose.Slides for C++ API 参考
description: 表示指定图表的数据标签图例键的显示行为。如果数据标签图例键可见，则为 True。写入 bool。
type: docs
weight: 105
url: /zh/aspose.slides.charts/idatalabelformat/set_showlegendkey/
---
## IDataLabelFormat::set_ShowLegendKey(bool) 方法

表示指定图表的数据标签图例键的显示行为。如果数据标签图例键可见，则为 True。写入 **bool**。

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowLegendKey(bool value)=0
```

## 备注

如果此 [DataLabelFormat](../../datalabelformat/) 对象的父对象是 [DataLabelCollection](../../datalabelcollection/) 数据标签集合，则此属性获取或设置 [DataLabelCollection](../../datalabelcollection/) 集合中新数据标签的 ShowLegendKey 属性的默认值。使用该值设置此属性时，还会将此值设置为 [DataLabelCollection](../../datalabelcollection/) 集合中所有数据标签的 ShowLegendKey 属性（即 "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" 导致所有 DataLabels[i].ShowLegendKey 等于 val）。

## 另请参见

* 类 [IDataLabelFormat](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)
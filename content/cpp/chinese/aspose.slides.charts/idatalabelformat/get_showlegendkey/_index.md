---
title: get_ShowLegendKey()
second_title: Aspose.Slides for C++ API 参考
description: 表示指定图表的数据标签图例键的显示行为。如果数据标签图例键可见，则为 true。读取 bool.
type: docs
weight: 92
url: /zh/aspose.slides.charts/idatalabelformat/get_showlegendkey/
---
## IDataLabelFormat::get_ShowLegendKey() 方法


表示指定图表的数据标签图例键的显示行为。如果数据标签图例键可见，则为 true。读取 **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowLegendKey()=0
```

## 备注


如果此 [DataLabelFormat](../../datalabelformat/) 对象的父级是 [DataLabelCollection](../../datalabelcollection/) 数据标签集合，则此属性获取或设置 [DataLabelCollection](../../datalabelcollection/) 集合中新数据标签的 ShowLegendKey 属性的默认值。使用该值设置此属性还会将该值设置为 [DataLabelCollection](../../datalabelcollection/) 集合中所有数据标签的 ShowLegendKey 属性（即 "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" 会导致所有 DataLabels[i].ShowLegendKey 等于 val）。 



## 另见

* 类 [IDataLabelFormat](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)
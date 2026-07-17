---
title: set_Position()
second_title: Aspose.Slides C++ API 参考
description: 表示数据标签的位置。写入 LegendDataLabelPosition.
type: docs
weight: 79
url: /zh/aspose.slides.charts/idatalabelformat/set_position/
---
## IDataLabelFormat::set_Position(LegendDataLabelPosition) 方法


表示数据标签的位置。写入 [LegendDataLabelPosition](../../legenddatalabelposition/).

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_Position(LegendDataLabelPosition value)=0
```

## 备注


如果此 [DataLabelFormat](../../datalabelformat/) 对象的父级是 [DataLabelCollection](../../datalabelcollection/) 数据标签集合，则此属性获取或设置 [DataLabelCollection](../../datalabelcollection/) 集合中新数据标签的 Position 属性的默认值。表示
位置 对于 [DataLabel](../../datalabel/) 对象。为此属性设置值时，也会将该值设置为 [DataLabelCollection](../../datalabelcollection/) 集合中所有数据标签的 Position 属性 (例如 \"DataLabels.DefaultDataLabelFormat.Position = val;\"，导致所有 DataLabels[i].Position 等于 val)。 


## 参见

* 枚举 [LegendDataLabelPosition](../../legenddatalabelposition/)
* 类 [IDataLabelFormat](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)
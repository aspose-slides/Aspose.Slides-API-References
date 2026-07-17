---
title: get_Position()
second_title: Aspose.Slides C++ API 参考
description: 表示数据标签的位置。请参阅 LegendDataLabelPosition。
type: docs
weight: 66
url: /zh/aspose.slides.charts/idatalabelformat/get_position/
---
## IDataLabelFormat::get_Position() 方法

表示数据标签的位置。请参阅 [LegendDataLabelPosition](../../legenddatalabelposition/)。

```cpp
virtual LegendDataLabelPosition Aspose::Slides::Charts::IDataLabelFormat::get_Position()=0
```

## 备注

如果此 [DataLabelFormat](../../datalabelformat/) 对象的父对象是一个 [DataLabelCollection](../../datalabelcollection/) 数据标签集合，则此属性获取或设置 [DataLabelCollection](../../datalabelcollection/) 集合中新数据标签的 Position 属性的默认值。表示 [DataLabel](../../datalabel/) 对象的位置。将此属性设置为某个值时，还会将该值设置为 [DataLabelCollection](../../datalabelcollection/) 集合中所有数据标签的 Position 属性（即 "DataLabels.DefaultDataLabelFormat.Position = val;" 导致所有 DataLabels[i].Position 等于 val）。

## 另见

* Enum [LegendDataLabelPosition](../../legenddatalabelposition/)
* 类 [IDataLabelFormat](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)
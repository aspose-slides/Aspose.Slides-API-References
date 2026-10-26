---
title: get_Separator()
second_title: Aspose.Slides for C++ API 参考
description: "设置或返回表示图表上数据标签使用的分隔符的 Variant。阅读 System::String."
type: docs
weight: 326
url: /zh/aspose.slides.charts/idatalabelformat/get_separator/
---
## IDataLabelFormat::get_Separator() 方法

设置或返回一个 Variant，表示图表上数据标签使用的分隔符。阅读 [System::String](../../../system/string/)。

```cpp
virtual System::String Aspose::Slides::Charts::IDataLabelFormat::get_Separator()=0
```

## 备注

如果此 [DataLabelFormat](../../datalabelformat/) 对象的父对象是 [DataLabelCollection](../../datalabelcollection/) 数据标签集合，则此属性获取或设置 [DataLabelCollection](../../datalabelcollection/) 集合中新数据标签的 Separator 属性的默认值。将此属性设置为某个值也会将该值设置为 [DataLabelCollection](../../datalabelcollection/) 集合中所有数据标签的 Separator 属性（例如 "DataLabels.DefaultDataLabelFormat.Separator = val;"，导致所有 DataLabels[i].Separator 均等于 val）。

## 另见

* 类 [String](../../../system/string/)
* 类 [IDataLabelFormat](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
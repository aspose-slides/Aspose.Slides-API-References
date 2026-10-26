---
title: set_Separator()
second_title: Aspose.Slides for C++ API 参考
description: "设置或返回一个 Variant，表示图表中数据标签使用的分隔符。写入 System::String。"
type: docs
weight: 339
url: /zh/aspose.slides.charts/idatalabelformat/set_separator/
---
## IDataLabelFormat::set_Separator(System::String) 方法

设置或返回一个 Variant，表示图表中数据标签使用的分隔符。写入 [System::String](../../../system/string/)。

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_Separator(System::String value)=0
```

## 备注

如果此 [DataLabelFormat](../../datalabelformat/) 对象的父对象是 [DataLabelCollection](../../datalabelcollection/) 数据标签集合，则此属性获取或设置 [DataLabelCollection](../../datalabelcollection/) 集合中新数据标签的 Separator 属性的默认值。使用该值设置此属性也会将此值设置为 [DataLabelCollection](../../datalabelcollection/) 集合中所有数据标签的 Separator 属性（即 "DataLabels.DefaultDataLabelFormat.Separator = val;" 导致所有 DataLabels[i].Separator 等于 val）。

## 另请参阅

* 类 [String](../../../system/string/)
* 类 [IDataLabelFormat](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)
---
title: get_Separator()
second_title: Aspose.Slides C++ API 参考
description: "设置或返回一个 Variant，表示图表上数据标签使用的分隔符。阅读 System::String."
type: docs
weight: 326
url: /zh/aspose.slides.charts/datalabelformat/get_separator/
---
## DataLabelFormat::get_Separator() 方法

设置或返回一个 Variant，表示图表上数据标签使用的分隔符。阅读 [System::String](../../../system/string/)。

```cpp
System::String Aspose::Slides::Charts::DataLabelFormat::get_Separator() override
```

## 备注

如果此 [DataLabelFormat](../) 对象的父对象是 [DataLabelCollection](../../datalabelcollection/) 数据标签集合，则此属性获取或设置 [DataLabelCollection](../../datalabelcollection/) 集合中新数据标签的 Separator 属性的默认值。使用该属性设置值时，还会将此值设置为 [DataLabelCollection](../../datalabelcollection/) 集合中所有数据标签的 Separator 属性（即 "DataLabels.DefaultDataLabelFormat.Separator = val;"，导致所有 DataLabels[i].Separator 等于 val）。 

## 另见

* 类 [String](../../../system/string/)
* 类 [DataLabelFormat](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)
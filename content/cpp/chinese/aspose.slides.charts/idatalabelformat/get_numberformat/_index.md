---
title: get_NumberFormat()
second_title: Aspose.Slides C++ API 参考
description: "表示 DataLabels 对象的格式字符串。阅读 System::String。"
type: docs
weight: 27
url: /zh/aspose.slides.charts/idatalabelformat/get_numberformat/
---
## IDataLabelFormat::get_NumberFormat() 方法

表示 DataLabels 对象的格式字符串。阅读 [System::String](../../../system/string/)。

```cpp
virtual System::String Aspose::Slides::Charts::IDataLabelFormat::get_NumberFormat()=0
```

## 备注



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```

如果此 [DataLabelFormat](../../datalabelformat/) 对象的父对象是一个 [DataLabelCollection](../../datalabelcollection/) 数据标签集合，则此属性获取或设置 [DataLabelCollection](../../datalabelcollection/) 集合中新数据标签的 NumberFormat 属性的默认值。当此属性被设置为某个值时，该值也会被设置为 [DataLabelCollection](../../datalabelcollection/) 集合中所有数据标签的 NumberFormat 属性（即 \"DataLabels.DefaultDataLabelFormat.NumberFormat = val;\" 会导致所有 DataLabels[i].NumberFormat 等于 val）。

## 参见

* 类 [String](../../../system/string/)
* 类 [IDataLabelFormat](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)
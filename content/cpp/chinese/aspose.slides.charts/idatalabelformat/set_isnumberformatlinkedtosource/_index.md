---
title: set_IsNumberFormatLinkedToSource()
second_title: Aspose.Slides C++ API 参考
description: 写 bool。
type: docs
weight: 14
url: /zh/aspose.slides.charts/idatalabelformat/set_isnumberformatlinkedtosource/
---
## IDataLabelFormat::set_IsNumberFormatLinkedToSource(bool) 方法

写 **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_IsNumberFormatLinkedToSource(bool value)=0
```

## 备注

如果此 [DataLabelFormat](../../datalabelformat/) 对象的父级是 [DataLabelCollection](../../datalabelcollection/) 数据标签集合，则此属性获取或设置 [DataLabelCollection](../../datalabelcollection/) 集合中新数据标签的 IsNumberFormatLinkedToSource 属性的默认值。将此属性设置为某个值时，也会将该值设置到 [DataLabelCollection](../../datalabelcollection/) 集合中所有数据标签的 IsNumberFormatLinkedToSource 属性 (即 "DataLabels.DefaultDataLabelFormat.IsNumberFormatLinkedToSource = val;" 会导致所有 DataLabels[i].IsNumberFormatLinkedToSource 等于 val)。

## 另见

* 类 [IDataLabelFormat](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)
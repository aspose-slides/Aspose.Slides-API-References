---
title: set_IsNumberFormatLinkedToSource()
second_title: Aspose.Slides for C++ API 参考
description: 写入 bool.
type: docs
weight: 14
url: /zh/aspose.slides.charts/datalabelformat/set_isnumberformatlinkedtosource/
---
## DataLabelFormat::set_IsNumberFormatLinkedToSource(bool) 方法

写入 **bool**.

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_IsNumberFormatLinkedToSource(bool value) override
```

## 备注

如果此 [DataLabelFormat](../) 对象的父级是 [DataLabelCollection](../../datalabelcollection/) 数据标签集合，则此属性获取或设置 [DataLabelCollection](../../datalabelcollection/) 集合中新建数据标签的 IsNumberFormatLinkedToSource 属性的默认值。将此属性设为某个值时，还会将该值设置为 [DataLabelCollection](../../datalabelcollection/) 集合中所有数据标签的 IsNumberFormatLinkedToSource 属性 (即 \"DataLabels.DefaultDataLabelFormat.IsNumberFormatLinkedToSource = val;\"，导致所有 DataLabels[i].IsNumberFormatLinkedToSource 均等于 val)。

## 参见

* 类 [DataLabelFormat](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)
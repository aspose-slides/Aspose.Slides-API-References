---
title: get_ShowBubbleSize()
second_title: Aspose.Slides for C++ API 参考
description: 表示指定图表的数据标签气泡大小值的显示行为。True 显示气泡大小值。False 隐藏。读取 bool.
type: docs
weight: 222
url: /zh/aspose.slides.charts/idatalabelformat/get_showbubblesize/
---
## IDataLabelFormat::get_ShowBubbleSize() 方法


表示指定图表的数据标签气泡大小值的显示行为。True 表示显示气泡大小值。False 表示隐藏。读取 **bool**。

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowBubbleSize()=0
```

## 备注


如果此 [DataLabelFormat](../../datalabelformat/) 对象的父级是一个 [DataLabelCollection](../../datalabelcollection/) 数据标签集合，则此属性获取或设置 [DataLabelCollection](../../datalabelcollection/) 集合中新数据标签的 ShowBubbleSize 属性的默认值。将此属性设置为某个值时，也会将该值设置为 [DataLabelCollection](../../datalabelcollection/) 集合中所有数据标签的 ShowBubbleSize 属性 (即 "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;"，导致所有 DataLabels[i].ShowBubbleSize 等于 val)。 
## 另请参阅

* 类 [IDataLabelFormat](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)
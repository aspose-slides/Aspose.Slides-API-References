---
title: get_ShowValue()
second_title: Aspose.Slides for C++ API 参考
description: 表示指定图表的数据标签百分比值的显示行为。True 显示百分比值。False 隐藏。读取 bool。
type: docs
weight: 118
url: /zh/aspose.slides.charts/idatalabelformat/get_showvalue/
---
## IDataLabelFormat::get_ShowValue() 方法


表示指定图表的数据标签百分比值的显示行为。True 表示显示百分比值。False 表示隐藏。读取 **bool**。

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowValue()=0
```

## 备注


如果此 [DataLabelFormat](../../datalabelformat/) 对象的父对象是 [DataLabelCollection](../../datalabelcollection/) 数据标签集合，则此属性获取或设置 [DataLabelCollection](../../datalabelcollection/) 集合中新数据标签的 ShowValue 属性的默认值。使用该值设置此属性时，也会将此值设置为 [DataLabelCollection](../../datalabelcollection/) 集合中所有数据标签的 ShowValue 属性（即 \"DataLabels.DefaultDataLabelFormat.ShowValue = val;\" 导致所有 DataLabels[i].ShowValue 等于 val）。 



## 另见

* 类 [IDataLabelFormat](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)
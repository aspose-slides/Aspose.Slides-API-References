---
title: get_ShowLabelAsDataCallout()
second_title: Aspose.Slides for C++ API 参考
description: 确定指定图表的数据标签是显示为数据标注还是显示为数据标签。
type: docs
weight: 274
url: /zh/aspose.slides.charts/idatalabelformat/get_showlabelasdatacallout/
---
## IDataLabelFormat::get_ShowLabelAsDataCallout() 方法


确定指定图表的数据标签是显示为数据标注还是显示为数据标签。

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowLabelAsDataCallout()=0
```

## 备注


如果此 [DataLabelFormat](../../datalabelformat/) 对象的父对象是 [DataLabelCollection](../../datalabelcollection/) 数据标签集合，则此属性获取或设置 [DataLabelCollection](../../datalabelcollection/) 集合中新数据标签的 ShowLabelAsDataCallout 属性的默认值。将此属性设置为某个值还会将该值设置为 [DataLabelCollection](../../datalabelcollection/) 集合中所有数据标签的 ShowLabelAsDataCallout 属性 (例如 "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" 会导致所有 DataLabels[i].ShowLabelAsDataCallout 等于 val)。 
## 另见

* 类 [IDataLabelFormat](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)
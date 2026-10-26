---
title: set_ShowLabelValueFromCell()
second_title: Aspose.Slides C++ API 参考
description: 表示指定图表的数据标签单元格值的显示行为。True 显示单元格值。False 隐藏。写入 bool。
type: docs
weight: 313
url: /zh/aspose.slides.charts/idatalabelformat/set_showlabelvaluefromcell/
---
## IDataLabelFormat::set_ShowLabelValueFromCell(bool) 方法

表示指定图表的数据标签单元格值的显示行为。True 显示单元格值。False 隐藏。写入 **bool**。

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowLabelValueFromCell(bool value)=0
```

## 备注

如果此 [DataLabelFormat](../../datalabelformat/) 对象的父对象是 [DataLabelCollection](../../datalabelcollection/) 数据标签集合，则此属性获取或设置 [DataLabelCollection](../../datalabelcollection/) 集合中新数据标签的 ShowLabelValueFromCell 属性的默认值。使用该值设置此属性还会将此值设置为 [DataLabelCollection](../../datalabelcollection/) 集合中所有数据标签的 ShowLabelValueFromCell 属性（即 "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" 使所有 DataLabels[i].ShowLabelValueFromCell 等于 val）。

## 另见

* 类 [IDataLabelFormat](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)
---
title: get_ShowLabelValueFromCell()
second_title: Aspose.Slides for C++ API 参考
description: 表示指定图表的数据标签单元格值的显示行为。True 显示单元格值。False 隐藏。读取 bool.
type: docs
weight: 300
url: /zh/aspose.slides.charts/idatalabelformat/get_showlabelvaluefromcell/
---
## IDataLabelFormat::get_ShowLabelValueFromCell() 方法


表示指定图表的数据标签单元格值的显示行为。True 显示单元格值。False 隐藏。读取 **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowLabelValueFromCell()=0
```

## 备注


如果此 [DataLabelFormat](../../datalabelformat/) 对象的父对象是 [DataLabelCollection](../../datalabelcollection/) 数据标签集合，则此属性获取或设置 [DataLabelCollection](../../datalabelcollection/) 集合中新数据标签的 ShowLabelValueFromCell 属性的默认值。将该属性设置为某个值时，也会将此值设置到 [DataLabelCollection](../../datalabelcollection/) 集合中所有数据标签的 ShowLabelValueFromCell 属性（即 "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" 会导致所有 DataLabels[i].ShowLabelValueFromCell 等于 val）。

## 另请参见

* 类 [IDataLabelFormat](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)
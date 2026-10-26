---
title: get_ShowCategoryName()
second_title: Aspose.Slides for C++ API 参考
description: 表示指定图表的数据标签类别名称的显示行为。True 表示在图表上的数据标签显示类别名称。False 表示隐藏。读取 bool。
type: docs
weight: 144
url: /zh/aspose.slides.charts/idatalabelformat/get_showcategoryname/
---
## IDataLabelFormat::get_ShowCategoryName() method

表示指定图表的数据标签类别名称的显示行为。True 表示在图表上的数据标签显示类别名称。False 表示隐藏。读取 **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowCategoryName()=0
```

## 备注

如果此 [DataLabelFormat](../../datalabelformat/) 对象的父对象是一个 [DataLabelCollection](../../datalabelcollection/) 数据标签集合，则此属性获取或设置 [DataLabelCollection](../../datalabelcollection/) 集合中新数据标签的 ShowCategoryName 属性的默认值。使用该值设置此属性也会将该值设置为 [DataLabelCollection](../../datalabelcollection/) 集合中所有数据标签的 ShowCategoryName 属性（即 "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" 导致所有 DataLabels[i].ShowCategoryName 等于 val）。

## 另请参见

* 类 [IDataLabelFormat](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)
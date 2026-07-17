---
title: set_ShowCategoryName()
second_title: Aspose.Slides for C++ API 参考
description: 表示指定图表的数据标签类别名称的显示行为。True 表示在图表的数据标签上显示类别名称。False 表示隐藏。写入 bool。
type: docs
weight: 157
url: /zh/aspose.slides.charts/idatalabelformat/set_showcategoryname/
---
## IDataLabelFormat::set_ShowCategoryName(bool) 方法

表示指定图表的数据标签类别名称的显示行为。True 表示在图表的数据标签上显示类别名称。False 表示隐藏。写入 **bool**。

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowCategoryName(bool value)=0
```

## 备注

如果此 [DataLabelFormat](../../datalabelformat/) 对象的父对象是一个 [DataLabelCollection](../../datalabelcollection/) 数据标签集合，则此属性获取或设置 [DataLabelCollection](../../datalabelcollection/) 集合中新数据标签的 ShowCategoryName 属性的默认值。使用该值设置此属性还会将此值设置为 [DataLabelCollection](../../datalabelcollection/) 集合中所有数据标签的 ShowCategoryName 属性（例如 "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" 导致所有 DataLabels[i].ShowCategoryName 等于 val）。

## 参见

* 类 [IDataLabelFormat](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)
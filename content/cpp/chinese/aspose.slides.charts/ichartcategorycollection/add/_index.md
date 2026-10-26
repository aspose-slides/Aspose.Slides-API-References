---
title: Add()
second_title: Aspose.Slides for C++ API 参考
description: 如果集合中已存在该分类，则返回它。否则从 IChartDataCell 创建新的图表分类并将其添加到集合中。
type: docs
weight: 53
url: /zh/aspose.slides.charts/ichartcategorycollection/add/
---
## IChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) 方法

如果集合中已存在该分类，则返回它。否则从 [IChartDataCell](../../ichartdatacell/) 创建新的图表分类并将其添加到集合中。

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) 用于创建图表分类。 |

### 返回值

已添加的或已存在的分类。

## IChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) 方法

从值创建新的 [IChartCategory](../../ichartcategory/) 并将其添加到集合中。

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<System::Object> value)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 该值。 |

### 返回值

已添加 [IChartCategory](../../ichartcategory/)。

## 备注

此方法会添加名称为 AUTO_DATA 的工作表并将所有值添加到该工作表。如果使用 [IChartDataWorkbook](../../ichartdataworkbook/) 添加或编辑单元格的值，请确保不要使用此工作表。使用此方法添加的值的最大数量不得超过 16711680。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IChartCategory](../../ichartcategory/)
* 类 [IChartDataCell](../../ichartdatacell/)
* 类 [IChartCategoryCollection](../)
* 类 [Object](../../../system/object/)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)
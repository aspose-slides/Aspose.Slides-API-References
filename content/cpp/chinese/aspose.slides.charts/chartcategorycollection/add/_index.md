---
title: Add()
second_title: Aspose.Slides C++ API 参考
description: 如果集合中已存在类别，则返回它。否则从 IChartDataCell 创建新的图表类别并将其添加到集合中。
type: docs
weight: 92
url: /zh/aspose.slides.charts/chartcategorycollection/add/
---
## ChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) 方法

如果集合中已有类别，则返回它。否则从 [IChartDataCell](../../ichartdatacell/) 创建新的图表类别并将其添加到集合中。

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell) override
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) 用于创建图表类别。 |

### 返回值

已添加或已存在的类别。

## ChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) 方法

从值创建新的 [ChartCategory](../../chartcategory/) 并将其添加到集合中。

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<System::Object> value) override
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 该值。 |

### 返回值

已添加 [IChartCategory](../../ichartcategory/)。

## 备注

此方法添加名为 AUTO_DATA 的工作表并在其中添加所有值。如果使用 [ChartDataWorkbook](../../chartdataworkbook/) 添加或编辑单元格值，请确保不要使用此工作表。使用此方法添加的值的最大数量不得超过 16711680。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IChartCategory](../../ichartcategory/)
* 类 [IChartDataCell](../../ichartdatacell/)
* 类 [ChartCategoryCollection](../)
* 类 [Object](../../../system/object/)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)
---
title: Add()
second_title: Aspose.Slides C++ API 参考
description: 向集合中添加新单元格。
type: docs
weight: 53
url: /zh/aspose.slides.charts/ichartcellcollection/add/
---
## IChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) 方法

向集合中添加新单元格。

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 要添加的新单元格。 |

## IChartCellCollection::Add(System::SharedPtr\<System::Object\>) 方法

从指定值创建[IChartDataCell](../../ichartdatacell/)并将其添加到集合中。

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<System::Object> value)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 值。 |

## 备注

此方法会添加名为 AUTO_DATA 的工作表并在其中添加所有值。若使用[IChartDataWorkbook](../../ichartdataworkbook/)添加或编辑[Cell](../../../aspose.slides/cell/)值，请确保不要使用此工作表。使用此方法添加的值的最大数量不得超过 16711680

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IChartDataCell](../../ichartdatacell/)
* 类 [IChartCellCollection](../)
* 类 [Object](../../../system/object/)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)
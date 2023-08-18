---
title: Add()
second_title: Aspose.Slides for C++ API Reference
description: Add new cell to the collection.
type: docs
weight: 53
url: /aspose.slides.charts/chartcellcollection/add/
---
## ChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) method


Add new cell to the collection.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<IChartDataCell> cell) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| cell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | New cell to add. |

## ChartCellCollection::Add(System::SharedPtr\<System::Object\>) method


Creates [ChartDataCell](../../chartdatacell/) from specified value and adds it to the collection.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<System::Object> value) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | The value. |
## Remarks



This method adds worksheet with name AUTO_DATA and adds all values there. If you use [ChartDataWorkbook](../../chartdataworkbook/) to add or edit [Cell](../../../aspose.slides/cell/) values, be sure that you do not use this worksheet Maximum number of values added using this method must not exceed 16711680



## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [ChartCellCollection](../)
* Class [Object](../../../system/object/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
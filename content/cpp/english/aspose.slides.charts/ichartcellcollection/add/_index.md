---
title: Add()
second_title: Aspose.Slides for C++ API Reference
description: Add new cell to the collection.
type: docs
weight: 53
url: /aspose.slides.charts/ichartcellcollection/add/
---
## IChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) method


Add new cell to the collection.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | New cell to add. |

## IChartCellCollection::Add(System::SharedPtr\<System::Object\>) method


Creates [IChartDataCell](../../ichartdatacell/) from specified value and adds it to the collection.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<System::Object> value)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | The value. |
## Remarks



This method adds worksheet with name AUTO_DATA and adds all values there. If you use [IChartDataWorkbook](../../ichartdataworkbook/) to add or edit [Cell](../../../aspose.slides/cell/) values, be sure that you do not use this worksheet Maximum number of values added using this method must not exceed 16711680



## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartCellCollection](../)
* Class [Object](../../../system/object/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
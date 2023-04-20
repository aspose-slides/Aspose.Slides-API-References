---
title: Add()
second_title: Aspose.Slides for C++ API Reference
description: If category exists in collection, return it. Else creates new chart category from IChartDataCell and adds it to the collection.
type: docs
weight: 53
url: /cpp/aspose.slides.charts/ichartcategorycollection/add/
---
## IChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) method


If category exists in collection, return it. Else creates new chart category from [IChartDataCell](../../ichartdatacell/) and adds it to the collection.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) used to create chart category. |

### Return Value

Added or existing category.



## IChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) method


Creates new [IChartCategory](../../ichartcategory/) from value and adds it to the collection.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<System::Object> value)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | The value. |

### Return Value

Added [IChartCategory](../../ichartcategory/).
## Remarks



This method adds worksheet with name AUTO_DATA and adds all values there. If you use [IChartDataWorkbook](../../ichartdataworkbook/) to add or edit cell values, be sure that you do not use this worksheet Maximum number of values added using this method must not exceed 16711680



## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartCategory](../../ichartcategory/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartCategoryCollection](../)
* Class [Object](../../../system/object/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
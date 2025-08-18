---
title: GetCellCollection()
second_title: Aspose.Slides for C++ API Reference
description: Gets the set of cells.
type: docs
weight: 27
url: /aspose.slides.charts/ichartdataworkbook/getcellcollection/
---
## IChartDataWorkbook::GetCellCollection(System::String, bool) method


Gets the set of cells.

```cpp
virtual System::SharedPtr<IChartCellCollection> Aspose::Slides::Charts::IChartDataWorkbook::GetCellCollection(System::String formula, bool skipHiddenCells)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | [Excel](../../../aspose.slides.excel/) formula like \"Sheet1!$A$2:$A$5\". |
| skipHiddenCells | **bool** | If true then method returns collection without hidden cells. |

### Return Value

Set of cells [IChartCellCollection](../../ichartcellcollection/)

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartCellCollection](../../ichartcellcollection/)
* Class [String](../../../system/string/)
* Class [IChartDataWorkbook](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
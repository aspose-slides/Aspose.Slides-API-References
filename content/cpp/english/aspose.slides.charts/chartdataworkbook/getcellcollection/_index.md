---
title: GetCellCollection()
second_title: Aspose.Slides for C++ API Reference
description: Gets the set of cells.
type: docs
weight: 14
url: /aspose.slides.charts/chartdataworkbook/getcellcollection/
---
## ChartDataWorkbook::GetCellCollection(System::String, bool) method


Gets the set of cells.

```cpp
System::SharedPtr<IChartCellCollection> Aspose::Slides::Charts::ChartDataWorkbook::GetCellCollection(System::String formula, bool skipHiddenCells) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | Excel formula like \"Sheet1!$A$2:$A$5\". |
| skipHiddenCells | **bool** | If true then method returns collection without hidden cells. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartCellCollection](../../ichartcellcollection/)
* Class [String](../../../system/string/)
* Class [ChartDataWorkbook](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
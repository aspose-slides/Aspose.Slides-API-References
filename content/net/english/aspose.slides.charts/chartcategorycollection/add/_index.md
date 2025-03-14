---
title: Add
second_title: Aspose.Sildes for .NET API Reference
description: If category exists in collection return it. Else creates new chart category from IChartDataCellaspose.slides.charts/ichartdatacell and adds it to the collection.
type: docs
weight: 70
url: /aspose.slides.charts/chartcategorycollection/add/
---

## Add(IChartDataCell) {#add}

If category exists in collection, return it. Else creates new chart category from [`IChartDataCell`](../../ichartdatacell) and adds it to the collection.

```csharp
public IChartCategory Add(IChartDataCell chartDataCell)
```

| Parameter | Type | Description |
| --- | --- | --- |
| chartDataCell | IChartDataCell | Cell used to create chart category. |

### Return Value

Added or existing category.

### See Also

* interface [IChartCategory](../../ichartcategory)
* interface [IChartDataCell](../../ichartdatacell)
* class [ChartCategoryCollection](../../chartcategorycollection)
* namespace [Aspose.Slides.Charts](../../chartcategorycollection)
* assembly [Aspose.Slides](../../../)

---

## Add(object) {#add_1}

Creates new [`ChartCategory`](../../chartcategory) from value and adds it to the collection.

```csharp
public IChartCategory Add(object value)
```

| Parameter | Type | Description |
| --- | --- | --- |
| value | Object | The value. |

### Return Value

Added [`IChartCategory`](../../ichartcategory).

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | if limit exceeded |

### Remarks

This method adds worksheet with name AUTO_DATA and adds all values there. If you use [`ChartDataWorkbook`](../../chartdataworkbook) to add or edit cell values, be sure that you do not use this worksheet Maximum number of values added using this method must not exceed 16711680

### See Also

* interface [IChartCategory](../../ichartcategory)
* class [ChartCategoryCollection](../../chartcategorycollection)
* namespace [Aspose.Slides.Charts](../../chartcategorycollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->

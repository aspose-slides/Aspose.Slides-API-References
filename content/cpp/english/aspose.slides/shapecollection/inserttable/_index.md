---
title: InsertTable()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new table and inserts it into the shape collection at the specified index.
type: docs
weight: 482
url: /aspose.slides/shapecollection/inserttable/
---
## ShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) method


Creates a new table and inserts it into the shape collection at the specified index.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which to insert the table. |
| x | **float** | The x-coordinate of the table, in points. |
| y | **float** | The y-coordinate of the table, in points. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | An array of doubles representing the widths of the table\\u2019s columns, in points. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | An array of doubles representing the heights of the table\\u2019s rows, in points. |

### Return Value

The newly created [ITable](../../itable/).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ITable](../../itable/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
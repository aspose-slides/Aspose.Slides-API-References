---
title: InsertTable()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new Table and inserts it to the collection at the specified index.
type: docs
weight: 443
url: /cpp/aspose.slides/ishapecollection/inserttable/
---
## IShapeCollection::InsertTable(**int32_t**, **float**, **float**, [System::ArrayPtr](../../../system/arrayptr/)\<**double**\>, [System::ArrayPtr](../../../system/arrayptr/)\<**double**\>) method


Creates a new [Table](../../table/) and inserts it to the collection at the specified index.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which value should be inserted. |
| x | **float** | The X-coordinate for a left side of shape's frame. |
| y | **float** | The Y-coordinate for a top side of shape's frame. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Array of doubles which represents widths of columns in the table. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Array of doubles which represents heights of rows in the table. |

### Return Value

Created [Table](../../table/) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITable](../../itable/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)

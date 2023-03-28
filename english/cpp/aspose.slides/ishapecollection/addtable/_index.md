---
title: AddTable()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new Table and adds it to the end of the collection.
type: docs
weight: 430
url: /cpp/aspose.slides/ishapecollection/addtable/
---
## IShapeCollection::AddTable(**float**, **float**, [System::ArrayPtr](../../../system/arrayptr/)\<**double**\>, [System::ArrayPtr](../../../system/arrayptr/)\<**double**\>) method


Creates a new [Table](../../table/) and adds it to the end of the collection.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
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

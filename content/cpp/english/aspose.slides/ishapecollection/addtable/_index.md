---
title: AddTable()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new table and adds it to the end of the shape collection.
type: docs
weight: 430
url: /aspose.slides/ishapecollection/addtable/
---
## IShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) method


Creates a new table and adds it to the end of the shape collection.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
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
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
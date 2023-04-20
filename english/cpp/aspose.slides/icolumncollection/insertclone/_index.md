---
title: InsertClone()
second_title: Aspose.Slides for C++ API Reference
description: Creates a copy of the specified template column and insert it at the specified position in a table.
type: docs
weight: 27
url: /cpp/aspose.slides/icolumncollection/insertclone/
---
## IColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) method


Creates a copy of the specified template column and insert it at the specified position in a table.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Index of a new column. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) which is used as a template. |
| withAttachedColumns | **bool** | True to copy also all columns attached to the template column. |

### Return Value

Inserted columns.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColumn](../../icolumn/)
* Class [IColumnCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
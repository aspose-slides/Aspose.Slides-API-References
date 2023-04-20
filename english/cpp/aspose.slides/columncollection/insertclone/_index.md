---
title: InsertClone()
second_title: Aspose.Slides for C++ API Reference
description: Creates a copy of the specified template column and insert it at the specified position in a table.
type: docs
weight: 66
url: /cpp/aspose.slides/columncollection/insertclone/
---
## ColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) method


Creates a copy of the specified template column and insert it at the specified position in a table.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
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
* Class [ColumnCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
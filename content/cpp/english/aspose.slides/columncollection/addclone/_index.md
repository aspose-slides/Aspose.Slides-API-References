---
title: AddClone()
second_title: Aspose.Slides for C++ API Reference
description: Creates a copy of the specified template row and inserts it at the bottom of a table.
type: docs
weight: 53
url: /aspose.slides/columncollection/addclone/
---
## ColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) method


Creates a copy of the specified template row and inserts it at the bottom of a table.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) which is used as a template. |
| withAttachedColumns | **bool** | True to copy also all columns attached to the template row. |

### Return Value

Added columns.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColumn](../../icolumn/)
* Class [ColumnCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
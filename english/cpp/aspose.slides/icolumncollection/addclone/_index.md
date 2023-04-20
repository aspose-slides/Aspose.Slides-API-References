---
title: AddClone()
second_title: Aspose.Slides for C++ API Reference
description: Creates a copy of the specified template row and inserts it at the bottom of a table.
type: docs
weight: 14
url: /cpp/aspose.slides/icolumncollection/addclone/
---
## IColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) method


Creates a copy of the specified template row and inserts it at the bottom of a table.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
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
* Class [IColumnCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
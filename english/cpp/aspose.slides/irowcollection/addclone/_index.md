---
title: AddClone()
second_title: Aspose.Slides for C++ API Reference
description: Creates a copy of the specified template row and inserts it at the bottom of a table.
type: docs
weight: 14
url: /cpp/aspose.slides/irowcollection/addclone/
---
## IRowCollection::AddClone([System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\>, **bool**) method


Creates a copy of the specified template row and inserts it at the bottom of a table.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) which is used as a template. |
| withAttachedRows | **bool** | True to copy also all rows attached to the template row. |

### Return Value

Added rows.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IRow](../../irow/)
* Class [IRowCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)

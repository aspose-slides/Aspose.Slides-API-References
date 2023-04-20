---
title: InsertClone()
second_title: Aspose.Slides for C++ API Reference
description: Creates a copy of the specified template row and insert it at the specified position in a table.
type: docs
weight: 27
url: /cpp/aspose.slides/irowcollection/insertclone/
---
## IRowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) method


Creates a copy of the specified template row and insert it at the specified position in a table.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Index of a new row. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) which is used as a template. |
| withAttachedRows | **bool** | True to copy also all rows attached to the template row. |

### Return Value

Inserted rows.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IRow](../../irow/)
* Class [IRowCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
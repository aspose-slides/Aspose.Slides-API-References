---
title: InsertClone()
second_title: Aspose.Slides for C++ API Reference
description: Creates a copy of the specified template row and insert it at the specified position in a table.
type: docs
weight: 66
url: /cpp/aspose.slides/rowcollection/insertclone/
---
## RowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) method


Creates a copy of the specified template row and insert it at the specified position in a table.

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows) override
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
* Class [RowCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
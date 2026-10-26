---
title: InsertClone()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy kopię określonej kolumny szablonu i wstawia ją w określonej pozycji w tabeli.
type: docs
weight: 66
url: /pl/aspose.slides/columncollection/insertclone/
---
## ColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) metoda


Tworzy kopię określonej kolumny szablonu i wstawia ją w określonej pozycji w tabeli.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Indeks nowej kolumny. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) który jest używany jako szablon. |
| withAttachedColumns | **bool** | Prawda, aby również skopiować wszystkie kolumny dołączone do kolumny szablonu. |

### Return Value

Wstawione kolumny.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColumn](../../icolumn/)
* Class [ColumnCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
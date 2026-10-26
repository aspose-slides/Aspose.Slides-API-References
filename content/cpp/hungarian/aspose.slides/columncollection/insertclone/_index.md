---
title: InsertClone()
second_title: Aspose.Slides C++ API referenciája
description: Létrehoz egy másolatot a megadott sablonoszlopról, és beszúrja a táblázatban a megadott pozícióba.
type: docs
weight: 66
url: /hu/aspose.slides/columncollection/insertclone/
---
## ColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) metódus

Létrehoz egy másolatot a megadott sablonoszlopról, és beszúrja a megadott pozícióba egy táblázatban.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Az új oszlop indexe. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) amely sablonként használatos. |
| withAttachedColumns | **bool** | True, ha a sablon oszlophoz csatolt összes oszlopot is másolni szeretnénk. |

### Visszatérési érték

Beszúrt oszlopok.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IColumn](../../icolumn/)
* Osztály [ColumnCollection](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)
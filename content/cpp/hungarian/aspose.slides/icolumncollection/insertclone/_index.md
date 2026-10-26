---
title: InsertClone()
second_title: Aspose.Slides C++ API referencia
description: Létrehoz egy másolatot a megadott sablonoszlopról, és beilleszti azt a táblázat megadott pozíciójába.
type: docs
weight: 27
url: /hu/aspose.slides/icolumncollection/insertclone/
---
## IColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) method

Létrehoz egy másolatot a megadott sablonoszlopról, és beilleszti azt a táblázat megadott pozíciójába.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az új oszlop indexe. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) amely sablonként szolgál. |
| withAttachedColumns | **bool** | Igaz, ha másolni is szeretné az összes a sablonoszlophoz csatolt oszlopot. |

### Visszatérési érték

Beszúrt oszlopok.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IColumn](../../icolumn/)
* Osztály [IColumnCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)
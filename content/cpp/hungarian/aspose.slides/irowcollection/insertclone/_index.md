---
title: InsertClone()
second_title: Aspose.Slides C++ API-referencia
description: Létrehoz egy másolatot a megadott sablon sorból, és a táblázatban a megadott pozícióba szúrja be.
type: docs
weight: 27
url: /hu/aspose.slides/irowcollection/insertclone/
---
## IRowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) metódus

Létrehoz egy másolatot a megadott sablonsorból, és beszúrja a táblázatban a megadott pozícióba.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az új sor indexe. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) amely sablonként szolgál. |
| withAttachedRows | **bool** | True, ha másolni is kell a sablon sorhoz csatolt összes sort. |

### Visszatérési érték

Beszúrt sorok.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IRow](../../irow/)
* Osztály [IRowCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)
---
title: InsertClone()
second_title: Aspose.Slides C++ API referencia
description: Létrehoz egy másolatot a megadott sablon sorból, és beilleszti a táblázat megadott pozíciójába.
type: docs
weight: 66
url: /hu/aspose.slides/rowcollection/insertclone/
---
## RowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) metódus

Létrehoz egy másolatot a megadott sablon sorból, és beilleszti a táblázat megadott pozíciójába.

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az új sor indexe. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) amely sablonként van használva. |
| withAttachedRows | **bool** | True, ha a sablon sorhoz csatolt összes sort is másolni kell. |

### Visszatérési érték

Beillesztett sorok.

## Lásd még

* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IRow](../../irow/)
* Osztály [RowCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)
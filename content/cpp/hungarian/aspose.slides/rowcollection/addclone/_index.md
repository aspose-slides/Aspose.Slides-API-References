---
title: AddClone()
second_title: Aspose.Slides C++ API referencia
description: Létrehozza a megadott sablon sor másolatát, és a táblázat aljára illeszti be.
type: docs
weight: 53
url: /hu/aspose.slides/rowcollection/addclone/
---
## RowCollection::AddClone(System::SharedPtr\<IRow\>, bool) metódus

Létrehozza a megadott sablon sor másolatát és beszúrja a táblázat aljára.

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) amely sablonként használható. |
| withAttachedRows | **bool** | True, ha a sablon sorhoz csatolt összes sort is másolni szeretné. |

### Visszatérési érték

Hozzáadott sorok.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IRow](../../irow/)
* Osztály [RowCollection](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
---
title: AddClone()
second_title: Aspose.Slides C++ API referencia
description: Létrehoz egy másolatot a megadott sablon sorból, és a táblázat aljára illeszti.
type: docs
weight: 53
url: /hu/aspose.slides/columncollection/addclone/
---
## ColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) metódus


Létrehoz egy másolatot a megadott sablon sorról, és a táblázat aljára illeszti.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) amely sablonként használható. |
| withAttachedColumns | **bool** | Igaz, ha a sablon sorhoz csatolt összes oszlopot is másolni szeretné. |

### Visszatérési érték

Hozzáadott oszlopok.

## Lásd még

* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IColumn](../../icolumn/)
* Osztály [ColumnCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)
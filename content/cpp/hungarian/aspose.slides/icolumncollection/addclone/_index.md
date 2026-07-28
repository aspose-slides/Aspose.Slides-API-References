---
title: AddClone()
second_title: Aspose.Slides for C++ API Referenciája
description: Létrehozza a megadott sablon sor másolatát, és beszúrja a táblázat aljára.
type: docs
weight: 14
url: /hu/aspose.slides/icolumncollection/addclone/
---
## IColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) metódus


Létrehozza a megadott sablon sor másolatát, és beszúrja a táblázat aljára.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```


### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) amely sablonként használatos. |
| withAttachedColumns | **bool** | True a sablon sorhoz csatolt összes oszlop másolásához. |

### Visszatérési érték

Hozzáadott oszlopok.

## Lásd még

* typedef [ArrayPtr](../../../system/arrayptr/)
* typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IColumn](../../icolumn/)
* Osztály [IColumnCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)
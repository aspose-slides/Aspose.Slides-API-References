---
title: AddClone()
second_title: Aspose.Slides C++ API referencia
description: Létrehoz egy másolatot a megadott sablon sorból, és a táblázat aljára helyezi.
type: docs
weight: 14
url: /hu/aspose.slides/irowcollection/addclone/
---
## IRowCollection::AddClone(System::SharedPtr\<IRow\>, bool) metódus


Létrehoz egy másolatot a megadott sablon sorból, és a táblázat aljába helyezi.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) amely sablonként van használva. |
| withAttachedRows | **bool** | Igaz, ha a sablon sorhoz csatolt összes sort is másolni szeretné. |

### Visszatérési érték

Hozzáadott sorok.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IRow](../../irow/)
* Osztály [IRowCollection](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
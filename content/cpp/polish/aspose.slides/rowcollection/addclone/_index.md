---
title: AddClone()
second_title: Odwołanie API Aspose.Slides dla C++
description: Tworzy kopię określonego wiersza szablonu i wstawia ją na koniec tabeli.
type: docs
weight: 53
url: /pl/aspose.slides/rowcollection/addclone/
---
## RowCollection::AddClone(System::SharedPtr\<IRow\>, bool) metoda

Tworzy kopię określonego wiersza szablonu i wstawia ją na koniec tabeli.

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) używany jako szablon. |
| withAttachedRows | **bool** | True, aby skopiować także wszystkie wiersze dołączone do wiersza szablonu. |

### Wartość zwracana

Dodane wiersze.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IRow](../../irow/)
* Klasa [RowCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)
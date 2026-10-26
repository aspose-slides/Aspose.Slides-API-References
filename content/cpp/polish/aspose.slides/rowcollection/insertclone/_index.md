---
title: InsertClone()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy kopię określonego wiersza szablonu i wstawia ją w określonej pozycji w tabeli.
type: docs
weight: 66
url: /pl/aspose.slides/rowcollection/insertclone/
---
## RowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) metoda

Tworzy kopię określonego wiersza szablonu i wstawia ją w określonej pozycji w tabeli.

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks nowego wiersza. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) używany jako szablon. |
| withAttachedRows | **bool** | True aby również skopiować wszystkie wiersze dołączone do wiersza szablonu. |

### Wartość zwracana

Wstawione wiersze.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IRow](../../irow/)
* Klasa [RowCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)
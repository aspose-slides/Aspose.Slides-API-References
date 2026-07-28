---
title: InsertClone()
second_title: Aspose.Slides dla C++ - Referencja API
description: Tworzy kopię określonego wiersza szablonu i wstawia ją w określonej pozycji w tabeli.
type: docs
weight: 27
url: /pl/aspose.slides/irowcollection/insertclone/
---
## IRowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) metoda

Tworzy kopię określonego wiersza szablonu i wstawia ją w określonej pozycji w tabeli.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks nowego wiersza. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) używany jako szablon. |
| withAttachedRows | **bool** | Prawda, aby również skopiować wszystkie wiersze dołączone do wiersza szablonu. |

### Wartość zwracana

Wstawione wiersze.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IRow](../../irow/)
* Klasa [IRowCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
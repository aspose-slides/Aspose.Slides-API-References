---
title: InsertClone()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy kopię określonej kolumny szablonu i wstawia ją w określonej pozycji w tabeli.
type: docs
weight: 27
url: /pl/aspose.slides/icolumncollection/insertclone/
---
## IColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) metoda

Tworzy kopię określonej kolumny szablonu i wstawia ją w określonej pozycji w tabeli.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks nowej kolumny. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) który jest używany jako szablon. |
| withAttachedColumns | **bool** | True aby skopiować również wszystkie kolumny dołączone do kolumny szablonu. |

### Wartość zwracana

Wstawione kolumny.

## Zobacz także

* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IColumn](../../icolumn/)
* Klasa [IColumnCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)
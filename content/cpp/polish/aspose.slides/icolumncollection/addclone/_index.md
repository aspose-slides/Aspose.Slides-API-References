---
title: AddClone()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Tworzy kopię określonego wiersza szablonu i wstawia ją na dole tabeli.
type: docs
weight: 14
url: /pl/aspose.slides/icolumncollection/addclone/
---
## IColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) metoda

Tworzy kopię określonego wiersza szablonu i wstawia ją na dole tabeli.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) który jest używany jako szablon. |
| withAttachedColumns | **bool** | True aby również skopiować wszystkie kolumny dołączone do wiersza szablonu. |

### Wartość zwracana

Dodane kolumny.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IColumn](../../icolumn/)
* Klasa [IColumnCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
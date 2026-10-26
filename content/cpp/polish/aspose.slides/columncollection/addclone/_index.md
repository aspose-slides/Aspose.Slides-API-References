---
title: AddClone()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Tworzy kopię określonego wiersza szablonu i wstawia ją na dole tabeli.
type: docs
weight: 53
url: /pl/aspose.slides/columncollection/addclone/
---
## ColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) method


Tworzy kopię określonego wiersza szablonu i wstawia ją na dole tabeli.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) używany jako szablon. |
| withAttachedColumns | **bool** | True, aby również skopiować wszystkie kolumny podłączone do wiersza szablonu. |

### Wartość zwracana

Dodane kolumny.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IColumn](../../icolumn/)
* Klasa [ColumnCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
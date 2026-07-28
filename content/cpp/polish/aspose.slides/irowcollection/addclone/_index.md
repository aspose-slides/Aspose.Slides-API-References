---
title: AddClone()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy kopię określonego wiersza szablonu i wstawia ją na końcu tabeli.
type: docs
weight: 14
url: /pl/aspose.slides/irowcollection/addclone/
---
## IRowCollection::AddClone(System::SharedPtr\<IRow\>, bool) metoda

Tworzy kopię określonego wiersza szablonu i wstawia ją na końcu tabeli.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) który jest używany jako szablon. |
| withAttachedRows | **bool** | True, aby skopiować również wszystkie wiersze podłączone do wiersza szablonu. |

### Wartość zwracana

Dodane wiersze.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IRow](../../irow/)
* Klasa [IRowCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)
---
title: TryGetLast()
second_title: Aspose.Slides pro C++ API Reference
description: Pokusí se získat poslední prvek kolekce.
type: docs
weight: 261
url: /cs/system.collections.generic.details/trygetlast/
---
## System::Collections::Generic::Details::TryGetLast(IEnumerable\<T\>\&, bool\&) funkce


Snaží se získat poslední prvek kolekce.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetLast(IEnumerable<T> &enumerable, bool &found)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků kolekce. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | Kolekce, ze které má být získán prvek. |
| found | **bool**\& | Výstupní parametr. Vrací true, pokud kolekce obsahuje jakýkoli prvek. V opačném případě je vráceno false. |

### Návratová hodnota

Vrací poslední prvek kolekce. Výchozí hodnota typu bude vrácena, pokud je kolekce prázdná.

## Viz také

* Třída [IEnumerable](../../system.collections.generic/ienumerable/)
* Jmenný prostor [System::Collections::Generic::Details](../)
* Knihovna [Aspose.Slides](../../)
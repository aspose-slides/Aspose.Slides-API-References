---
title: TryGetFirst()
second_title: Aspose.Slides pro C++ API Reference
description: Zkouší získat první prvek kolekce.
type: docs
weight: 248
url: /cs/system.collections.generic.details/trygetfirst/
---
## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, bool\&) funkce

Zkouší získat první prvek kolekce.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, bool &found)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků kolekce. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | Kolekce, ze které se má prvek získat. |
| found | **bool**\& | Výstupní parametr. Vrací true, pokud kolekce obsahuje nějaký prvek. V opačném případě se vrátí false. |

### Návratová hodnota

Vrací první prvek kolekce. Výchozí hodnota typu bude vrácena, pokud je kolekce prázdná.

## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, const Func\<T, bool\>\&, bool\&) funkce

Zkouší získat první prvek kolekce, který splňuje predikátní funkci.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, const Func<T, bool> &predicate, bool &found)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků kolekce. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | Kolekce, ze které se má prvek získat. |
| predicate | const [Func](../../system/func/)\<T, **bool**\>\& | Predikátní funkce. |
| found | **bool**\& | Výstupní parametr. Vrací true, pokud kolekce obsahuje nějaký prvek. V opačném případě se vrátí false. |

### Návratová hodnota

Vrací první prvek kolekce. Výchozí hodnota typu bude vrácena, pokud není nalezen žádný prvek, který splňuje zadanou predikátní funkci.

## Viz také

* Třída [IEnumerable](../../system.collections.generic/ienumerable/)
* Třída [Func](../../system/func/)
* Obor názvů [System::Collections::Generic::Details](../)
* Library [Aspose.Slides](../../)
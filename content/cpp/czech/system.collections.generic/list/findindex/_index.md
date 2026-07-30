---
title: FindIndex()
second_title: Aspose.Slides pro C++ – API reference
description: Vyhledá prvek, který splňuje specifikovaný predikát.
type: docs
weight: 404
url: /cs/system.collections.generic/list/findindex/
---
## List::FindIndex(System::Predicate\<T\>) metoda

Vyhledá prvek, který splňuje specifikovaný predikát.

```cpp
int System::Collections::Generic::List<T>::FindIndex(System::Predicate<T> match)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Predikát použitý k ověření prvků. |

### Návratová hodnota

[Index](../../../system/index/) odpovídajícího prvku nebo -1, pokud není nalezen.

## List::FindIndex(int, System::Predicate\<T\>) metoda

Vyhledá prvek, který splňuje specifikovaný predikát.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, System::Predicate<T> match)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) od kterého začít hledání. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Predikát použitý k ověření prvků. |

### Návratová hodnota

[Index](../../../system/index/) odpovídajícího prvku nebo -1, pokud není nalezen.

## List::FindIndex(int, int, System::Predicate\<T\>) metoda

Vyhledá prvek, který splňuje specifikovaný predikát.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, int count, System::Predicate<T> match)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) od kterého začít hledání. |
| count | int | Počet prvků, které procházet. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Predikát použitý k ověření prvků. |

### Návratová hodnota

[Index](../../../system/index/) odpovídajícího prvku nebo -1, pokud není nalezen.

## Viz také

* Typedef [Predicate](../../../system/predicate/)
* Třída [List](../)
* Jmenný prostor [System::Collections::Generic](../../)
* Knihovna [Aspose.Slides](../../../)
---
title: FindIndex()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Wyszukuje element spełniający określony predykat.
type: docs
weight: 404
url: /pl/system.collections.generic/list/findindex/
---
## List::FindIndex(System::Predicate\<T\>) metoda

Wyszukuje element spełniający określony predykat.

```cpp
int System::Collections::Generic::List<T>::FindIndex(System::Predicate<T> match)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Predykat służący do sprawdzania elementów. |

### Wartość zwracana

[Index](../../../system/index/) dopasowanego elementu lub -1, jeśli nie znaleziono.

## List::FindIndex(int, System::Predicate\<T\>) metoda

Wyszukuje element spełniający określony predykat.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, System::Predicate<T> match)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) określający, od którego indeksu rozpocząć wyszukiwanie. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Predykat służący do sprawdzania elementów. |

### Wartość zwracana

[Index](../../../system/index/) dopasowanego elementu lub -1, jeśli nie znaleziono.

## List::FindIndex(int, int, System::Predicate\<T\>) metoda

Wyszukuje element spełniający określony predykat.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, int count, System::Predicate<T> match)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) określający, od którego indeksu rozpocząć wyszukiwanie. |
| count | int | Liczba elementów do przeszukania. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Predykat służący do sprawdzania elementów. |

### Wartość zwracana

[Index](../../../system/index/) dopasowanego elementu lub -1, jeśli nie znaleziono.

## Zobacz także

* Typedef [Predicate](../../../system/predicate/)
* Klasa [List](../)
* Przestrzeń nazw [System::Collections::Generic](../../)
* Biblioteka [Aspose.Slides](../../../)
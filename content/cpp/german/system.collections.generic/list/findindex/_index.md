---
title: FindIndex()
second_title: Aspose.Slides für C++ API-Referenz
description: Sucht ein Element, das einem bestimmten Prädikat entspricht.
type: docs
weight: 404
url: /de/system.collections.generic/list/findindex/
---
## List::FindIndex(System::Predicate\<T\>) Methode


Sucht ein Element, das einem bestimmten Prädikat entspricht.

```cpp
int System::Collections::Generic::List<T>::FindIndex(System::Predicate<T> match)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Prädikat, mit dem die Elemente überprüft werden. |

### Rückgabewert

[Index](../../../system/index/) des passenden Elements oder -1, wenn nicht gefunden.

## List::FindIndex(int, System::Predicate\<T\>) Methode


Sucht ein Element, das einem bestimmten Prädikat entspricht.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, System::Predicate<T> match)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) zum Starten der Suche ab. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Prädikat, mit dem die Elemente überprüft werden. |

### Rückgabewert

[Index](../../../system/index/) des passenden Elements oder -1, wenn nicht gefunden.

## List::FindIndex(int, int, System::Predicate\<T\>) Methode


Sucht ein Element, das einem bestimmten Prädikat entspricht.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, int count, System::Predicate<T> match)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) zum Starten der Suche ab. |
| count | int | Anzahl der zu durchsuchenden Elemente. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Prädikat, mit dem die Elemente überprüft werden. |

### Rückgabewert

[Index](../../../system/index/) des passenden Elements oder -1, wenn nicht gefunden.

## Siehe auch

* Typedef [Predicate](../../../system/predicate/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)
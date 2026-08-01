---
title: FindIndex()
second_title: Aspose.Slides voor C++ API-referentie
description: Zoekt naar een element dat voldoet aan een specifieke predikaat.
type: docs
weight: 404
url: /nl/system.collections.generic/list/findindex/
---
## List::FindIndex(System::Predicate\<T\>) methode

Zoekt naar een element dat voldoet aan een specifieke predikaat.

```cpp
int System::Collections::Generic::List<T>::FindIndex(System::Predicate<T> match)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Predikaat om elementen te controleren. |

### Retourwaarde

[Index](../../../system/index/) van het overeenkomstige element of -1 indien niet gevonden.

## List::FindIndex(int, System::Predicate\<T\>) methode

Zoekt naar een element dat voldoet aan een specifieke predikaat.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, System::Predicate<T> match)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) om de zoekopdracht te starten vanaf. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Predikaat om elementen te controleren. |

### Retourwaarde

[Index](../../../system/index/) van het overeenkomstige element of -1 indien niet gevonden.

## List::FindIndex(int, int, System::Predicate\<T\>) methode

Zoekt naar een element dat voldoet aan een specifieke predikaat.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, int count, System::Predicate<T> match)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) om de zoekopdracht te starten vanaf. |
| count | int | Aantal elementen om door te zoeken. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Predikaat om elementen te controleren. |

### Retourwaarde

[Index](../../../system/index/) van het overeenkomstige element of -1 indien niet gevonden.

## Zie ook

* Typedef [Predicate](../../../system/predicate/)
* Klasse [List](../)
* Naamruimte [System::Collections::Generic](../../)
* Bibliotheek [Aspose.Slides](../../../)
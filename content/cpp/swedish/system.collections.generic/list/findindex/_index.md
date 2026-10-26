---
title: FindIndex()
second_title: Aspose.Slides för C++ API-referens
description: Söker efter element som uppfyller ett specifikt predikat.
type: docs
weight: 404
url: /sv/system.collections.generic/list/findindex/
---
## List::FindIndex(System::Predicate\<T\>) metod


Söker efter element som uppfyller ett specifikt predikat.

```cpp
int System::Collections::Generic::List<T>::FindIndex(System::Predicate<T> match)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Predikat för att kontrollera element. |

### Returvärde

[Index](../../../system/index/) av matchande element eller -1 om det inte hittas.

## List::FindIndex(int, System::Predicate\<T\>) metod


Söker efter element som uppfyller ett specifikt predikat.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, System::Predicate<T> match)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) för att starta sökningen från. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Predikat för att kontrollera element. |

### Returvärde

[Index](../../../system/index/) av matchande element eller -1 om det inte hittas.

## List::FindIndex(int, int, System::Predicate\<T\>) metod


Söker efter element som uppfyller ett specifikt predikat.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, int count, System::Predicate<T> match)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) för att starta sökningen från. |
| count | int | Antal element att gå igenom. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Predikat för att kontrollera element. |

### Returvärde

[Index](../../../system/index/) av matchande element eller -1 om det inte hittas.

## Se även

* Typedef [Predicate](../../../system/predicate/)
* Klass [List](../)
* Namnrymd [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)
---
title: LINQ_Any()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer om en sekvens innehåller några element.
type: docs
weight: 157
url: /sv/system.collections.generic/ienumerable/linq_any/
---
## IEnumerable::LINQ_Any() metod


Bestämmer om en sekvens innehåller några element.

```cpp
bool System::Collections::Generic::IEnumerable<T>::LINQ_Any()
```


### Returvärde

Sant om källsekvensen innehåller några element; annars falskt.

## IEnumerable::LINQ_Any(std::function\<bool(T)>) metod


Bestämmer om något element i en sekvens finns eller uppfyller ett villkor.

```cpp
bool System::Collections::Generic::IEnumerable<T>::LINQ_Any(std::function<bool(T)> predicate)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | En funktion för att testa varje element mot ett villkor. |

### Returvärde

Sant om källsekvensen innehåller några element; annars falskt.

## Se även

* Klass [IEnumerable](../)
* Namnrymd [System::Collections::Generic](../../)
* Bibliotek [Aspose.Slides](../../../)
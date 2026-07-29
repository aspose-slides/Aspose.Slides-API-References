---
title: LINQ_FirstOrDefault()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar det första elementet i en sekvens, eller ett standardvärde om sekvensen är tom.
type: docs
weight: 66
url: /sv/system.collections.generic/ienumerable/linq_firstordefault/
---
## IEnumerable::LINQ_FirstOrDefault() metod


Returnerar det första elementet i en sekvens, eller ett standardvärde om sekvensen är tom.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault()
```


### Returvärde

Det första elementet i sekvensen eller standardvärde om sekvensen är tom.

## IEnumerable::LINQ_FirstOrDefault(std::function\<bool(T)>) metod


Returnerar det första elementet i sekvensen som uppfyller ett villkor eller ett standardvärde om inget sådant element hittas.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault(std::function<bool(T)> predicate)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | En funktion för att testa varje element för ett villkor. |

### Returvärde

default(T) om source är tom eller om inget element klarar testet som anges av predicate; annars det första elementet i source som klarar testet som anges av predicate.

## Se även

* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)
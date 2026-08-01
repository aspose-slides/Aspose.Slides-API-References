---
title: LINQ_FirstOrDefault()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert het eerste element van een reeks, of een standaardwaarde als de reeks leeg is.
type: docs
weight: 66
url: /nl/system.collections.generic/ienumerable/linq_firstordefault/
---
## IEnumerable::LINQ_FirstOrDefault() methode


Retourneert het eerste element van een reeks, of een standaardwaarde als de reeks leeg is.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault()
```


### Retourwaarde

Eerste element in de reeks of een standaard geconstrueerde waarde als de reeks leeg is.

## IEnumerable::LINQ_FirstOrDefault(std::function\<bool(T)>) methode


Retourneert het eerste element van de reeks dat aan een voorwaarde voldoet, of een standaardwaarde als geen dergelijk element wordt gevonden.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault(std::function<bool(T)> predicate)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | Een functie om elk element op een voorwaarde te testen. |

### Retourwaarde

default(T) als source leeg is of als geen element voldoet aan de test gespecificeerd door predicate; anders het eerste element in source dat voldoet aan de test gespecificeerd door predicate.

## Zie ook

* Klasse [IEnumerable](../)
* Naamruimte [System::Collections::Generic](../../)
* Bibliotheek [Aspose.Slides](../../../)
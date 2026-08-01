---
title: MakeYieldEnumerable()
second_title: Aspose.Slides voor C++ API Referentie
description: Maakt een IEnumerable van een yield-functie.
type: docs
weight: 2419
url: /nl/system/makeyieldenumerable/
---
## System::MakeYieldEnumerable(const Details::YieldFunction\<T\>\&) functie

Maakt een IEnumerable van een yield-functie.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerable<T>> System::MakeYieldEnumerable(const Details::YieldFunction<T> &fnc)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen in de reeks |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | De yield-functie die moet worden uitgevoerd |

### Retourwaarde

Gedeelde pointer naar de IEnumerable

## Zie ook

* Typedef [SharedPtr](../sharedptr/)
* Klasse [IEnumerable](../../system.collections.generic/ienumerable/)
* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)
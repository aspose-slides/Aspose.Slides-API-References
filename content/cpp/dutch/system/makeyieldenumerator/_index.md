---
title: MakeYieldEnumerator()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een IEnumerator aan vanuit een yield-functie.
type: docs
weight: 2432
url: /nl/system/makeyieldenumerator/
---
## System::MakeYieldEnumerator(const Details::YieldFunction<T>&) functie

Maakt een IEnumerator aan vanuit een yield-functie.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerator<T>> System::MakeYieldEnumerator(const Details::YieldFunction<T> &fnc)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | The type of elements in the sequence |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fnc | const Details::YieldFunction<T>& | The yield function to execute |

### Retourwaarde

Gedeelde pointer naar de IEnumerator

## Zie ook

* Typedef [SharedPtr](../sharedptr/)
* Klasse [IEnumerator](../../system.collections.generic/ienumerator/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)
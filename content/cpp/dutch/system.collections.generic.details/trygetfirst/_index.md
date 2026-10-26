---
title: TryGetFirst()
second_title: Aspose.Slides voor C++ API-referentie
description: Probeert het eerste element van de collectie te verkrijgen.
type: docs
weight: 248
url: /nl/system.collections.generic.details/trygetfirst/
---
## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, bool\&) functie

Probeert het eerste element van de collectie te verkrijgen.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, bool &found)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van de collectiekelementen. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | De collectie waaruit een element moet worden verkregen. |
| found | **bool**\& | De outputparameter. Retourneert true wanneer de collectie een element bevat. Anders wordt false geretourneerd. |

### Retourwaarde

Retourneert het eerste collectievelement. De standaardwaarde van het type wordt geretourneerd wanneer de collectie leeg is.

## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, const Func\<T, bool\>\&, bool\&) functie

Probeert het eerste element van de collectie te verkrijgen dat voldoet aan de predicaatfunctie.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, const Func<T, bool> &predicate, bool &found)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van de collectiekelementen. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | De collectie waaruit een element moet worden verkregen. |
| predicate | const [Func](../../system/func/)\<T, **bool**\>\& | De predicaatfunctie. |
| found | **bool**\& | De outputparameter. Retourneert true wanneer de collectie een element bevat. Anders wordt false geretourneerd. |

### Retourwaarde

Retourneert het eerste collectievelement. De standaardwaarde van het type wordt geretourneerd wanneer er geen element wordt gevonden dat voldoet aan de opgegeven predicaatfunctie.

## Zie ook

* Klasse [IEnumerable](../../system.collections.generic/ienumerable/)
* Klasse [Func](../../system/func/)
* Namespace [System::Collections::Generic::Details](../)
* Bibliotheek [Aspose.Slides](../../)
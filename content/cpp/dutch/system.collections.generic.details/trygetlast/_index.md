---
title: TryGetLast()
second_title: Aspose.Slides voor C++ API-referentie
description: Probeert het laatste element van de collectie op te halen.
type: docs
weight: 261
url: /nl/system.collections.generic.details/trygetlast/
---
## System::Collections::Generic::Details::TryGetLast(IEnumerable\<T\>\&, bool\&) functie


Probeert het laatste element van de collectie op te halen.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetLast(IEnumerable<T> &enumerable, bool &found)
```


### Sjabloonparameters

| Parameter | Omschrijving |
| --- | --- |
| T | The type of the collection elements. |

### Argumenten

| Parameter | Type | Omschrijving |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | De collectie waaruit een element moet worden verkregen. |
| found | **bool**\& | De uitgaande parameter. Retourneert true wanneer de collectie een element bevat. Anders wordt false geretourneerd. |

### Retourwaarde

Retourneert het laatste element van de collectie. De standaardwaarde van het type wordt geretourneerd wanneer de collectie leeg is.

## Zie ook

* Klasse [IEnumerable](../../system.collections.generic/ienumerable/)
* Naamruimte [System::Collections::Generic::Details](../)
* Bibliotheek [Aspose.Slides](../../)
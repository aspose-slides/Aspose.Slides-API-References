---
title: Handle()
second_title: Aspose.Slides voor C++ API-referentie
description: Roep een handlerfunctie aan voor elke interne exceptie en gooit alle niet-afgehandelde excepties opnieuw.
type: docs
weight: 66
url: /nl/system/details_aggregateexception/handle/
---
## Details_AggregateException::Handle(const Func\<Exception, bool\>\&) methode

Roept een handlerfunctie aan op elke inner Exception en gooit alle niet-afgehandelde excepties opnieuw.

```cpp
void System::Details_AggregateException::Handle(const Func<Exception, bool> &predicate)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| predicate | const [Func](../../func/)\<[Exception](../../exception/), **bool**\>\& | Een functie die een Exception neemt en true retourneert als deze is afgehandeld. |

## Opmerkingen

Als alle exceptions zijn afgehandeld, retourneert de methode normaal; anders wordt een nieuwe AggregateException die de niet-afgehandelde exceptions bevat, gegooid.

## Zie ook

* Typedef [Exception](../../exception/)
* Klasse [Func](../../func/)
* Klasse [Details_AggregateException](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)
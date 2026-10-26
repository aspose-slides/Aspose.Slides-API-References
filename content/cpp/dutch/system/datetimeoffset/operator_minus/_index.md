---
title: operator-()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een nieuw exemplaar van de DateTimeOffset-klasse dat de datum- en tijdwaarde vertegenwoordigt die het resultaat is van het aftrekken van de opgegeven tijdsduur van de waarde die wordt weergegeven door het huidige object.
type: docs
weight: 521
url: /nl/system/datetimeoffset/operator_minus/
---
## DateTimeOffset::operator-(TimeSpan) const methode


Retourneert een nieuw exemplaar van de [DateTimeOffset](../) klasse dat de datum- en tijdwaarde vertegenwoordigt die het resultaat is van het aftrekken van de opgegeven tijdsduur van de waarde die wordt weergegeven door het huidige object.

```cpp
DateTimeOffset System::DateTimeOffset::operator-(TimeSpan value) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | Een tijdsinterval om af te trekken |

### Retourwaarde

Een nieuw exemplaar van de [DateTimeOffset](../) klasse dat de datum- en tijdwaarde vertegenwoordigt die het resultaat is van het aftrekken van **value** van de waarde die wordt weergegeven door het huidige object.

## DateTimeOffset::operator-(const DateTimeOffset\&) const methode


Retourneert een exemplaar van de [TimeSpan](../../timespan/) klasse dat het tijdsinterval weergeeft tussen de datum- en tijdwaarden die worden vertegenwoordigd door het huidige en het opgegeven object.

```cpp
TimeSpan System::DateTimeOffset::operator-(const DateTimeOffset &other) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | Een exemplaar van de [DateTime](../../datetime/) klasse die één uiteinde van het te berekenen interval aangeeft |

### Retourwaarde

Een exemplaar van de [TimeSpan](../../timespan/) klasse dat het tijdsinterval weergeeft tussen de datum- en tijdwaarden die worden vertegenwoordigd door het huidige object en **other**.

## Zie ook

* Klasse [DateTimeOffset](../)
* Klasse [TimeSpan](../../timespan/)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)
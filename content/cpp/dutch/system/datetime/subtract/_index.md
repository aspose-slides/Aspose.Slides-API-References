---
title: Subtract()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een nieuw exemplaar van de DateTime klasse die de datum en tijdwaarde vertegenwoordigt die het resultaat is van het aftrekken van de opgegeven tijdsduur van de waarde die door het huidige object wordt vertegenwoordigd.
type: docs
weight: 326
url: /nl/system/datetime/subtract/
---
## DateTime::Subtract(TimeSpan) const methode

Retourneert een nieuw exemplaar van de [DateTime](../) klasse die de datum- en tijdwaarde vertegenwoordigt die het resultaat is van het aftrekken van de opgegeven tijdsduur van de waarde die door het huidige object wordt vertegenwoordigd.

```cpp
DateTime System::DateTime::Subtract(TimeSpan duration) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| duration | [TimeSpan](../../timespan/) | Een tijdsinterval om af te trekken |

### Retourwaarde

Een nieuw exemplaar van de [DateTime](../) klasse die de datum- en tijdwaarde vertegenwoordigt die het resultaat is van het aftrekken van **duration** van de waarde die door het huidige object wordt vertegenwoordigd.

## DateTime::Subtract(DateTime) const methode

Retourneert een exemplaar van de [TimeSpan](../../timespan/) klasse die het tijdsinterval tussen de datum- en tijdwaarden vertegenwoordigt die door het huidige en het opgegeven object worden vertegenwoordigd.

```cpp
constexpr TimeSpan System::DateTime::Subtract(DateTime value) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DateTime](../) | Een exemplaar van de [DateTime](../) klasse dat één uiteinde van het te berekenen interval aangeeft |

### Retourwaarde

Een exemplaar van de [TimeSpan](../../timespan/) klasse die het tijdsinterval tussen de datum- en tijdwaarden vertegenwoordigt die door het huidige object en **value** worden vertegenwoordigd.

## Zie ook

* Klasse [DateTime](../)
* Klasse [TimeSpan](../../timespan/)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)
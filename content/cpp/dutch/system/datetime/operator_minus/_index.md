---
title: operator-()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een nieuw exemplaar van de DateTime-klasse die de datum- en tijdwaarde vertegenwoordigt die het resultaat is van het aftrekken van de opgegeven tijdsduur van de waarde die wordt weergegeven door het huidige object.
type: docs
weight: 651
url: /nl/system/datetime/operator_minus/
---
## DateTime::operator-(TimeSpan) const methode


Retourneert een nieuw exemplaar van de [DateTime](../) klasse die de datum- en tijdwaarde vertegenwoordigt die het resultaat is van het aftrekken van de opgegeven tijdsduur van de waarde die wordt vertegenwoordigd door het huidige object.

```cpp
DateTime System::DateTime::operator-(TimeSpan value) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | Een tijdsinterval om af te trekken |

### Retourwaarde

Een nieuw exemplaar van de [DateTime](../) klasse die de datum- en tijdwaarde vertegenwoordigt die het resultaat is van het aftrekken van **value** van de waarde die wordt vertegenwoordigd door het huidige object.

## DateTime::operator-(DateTime) const methode


Retourneert een exemplaar van de [TimeSpan](../../timespan/) klasse die het tijdsinterval vertegenwoordigt tussen de datum- en tijdwaarden die worden vertegenwoordigd door het huidige en het opgegeven object.

```cpp
constexpr TimeSpan System::DateTime::operator-(DateTime value) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DateTime](../) | Een exemplaar van de [DateTime](../) klasse die één uiteinde van het te berekenen interval aangeeft |

### Retourwaarde

Een exemplaar van de [TimeSpan](../../timespan/) klasse die het tijdsinterval vertegenwoordigt tussen de datum- en tijdwaarden die worden vertegenwoordigd door het huidige object en **value**.

## Zie ook

* Klasse [DateTime](../)
* Klasse [TimeSpan](../../timespan/)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)
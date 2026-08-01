---
title: Round()
second_title: Aspose.Slides voor C++ API-referentie
description: Rondt de opgegeven waarde af op het dichtstbijzijnde gehele getal. Een parameter specificeert het gedrag van de functie als de opgegeven waarde even ver van twee dichtstbijzijnde getallen ligt.
type: docs
weight: 404
url: /nl/system/decimal/round/
---
## Decimal::Round(const Decimal\&, MidpointRounding) methode

Rondt de opgegeven waarde af op het dichtstbijzijnde gehele getal. Een parameter geeft het gedrag van de functie aan als de opgegeven waarde even ver van twee dichtstbijzijnde getallen ligt.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, MidpointRounding mode=MidpointRounding::ToEven)
```

### Argumenten

| Parameter | Type | Omschrijving |
| --- | --- | --- |
| d | const [Decimal](../)\& | De te ronden waarde |
| mode | [MidpointRounding](../../midpointrounding/) | Specificeert hoe het afronden moet worden uitgevoerd als **value** even ver van twee dichtstbijzijnde getallen ligt. |

### Retourwaarde

**d** afgerond op het dichtstbijzijnde gehele getal

## Decimal::Round(const Decimal\&, int, MidpointRounding) methode

Rondt de opgegeven waarde af op de dichtstbijzijnde waarde met het opgegeven aantal fractionele cijfers. Een parameter geeft het gedrag van de functie aan als de opgegeven waarde even ver van twee dichtstbijzijnde getallen ligt.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, int digits, MidpointRounding mode=MidpointRounding::ToEven)
```

### Argumenten

| Parameter | Type | Omschrijving |
| --- | --- | --- |
| d | const [Decimal](../)\& | De te ronden waarde |
| digits | int | Het aantal fractionele cijfers in de afgeronde waarde |
| mode | [MidpointRounding](../../midpointrounding/) | Specificeert hoe het afronden moet worden uitgevoerd als **value** even ver van twee dichtstbijzijnde getallen ligt. |

### Retourwaarde

Het getal met het opgegeven aantal cijfers dat het dichtstbij **value** ligt

## Zie ook

* Enum [MidpointRounding](../../midpointrounding/)
* Klasse [Decimal](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)
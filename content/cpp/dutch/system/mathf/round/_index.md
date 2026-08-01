---
title: Round()
second_title: Aspose.Slides voor C++ API-referentie
description: Rondt de opgegeven waarde af naar het dichtstbijzijnde gehele getal.
type: docs
weight: 157
url: /nl/system/mathf/round/
---
## MathF::Round(float) methode

Rondt de opgegeven waarde af naar het dichtstbijzijnde gehele getal.

```cpp
static float System::MathF::Round(float a)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | **float** | De waarde die afgerond moet worden |

### Retourwaarde

**a** afgerond naar het dichtstbijzijnde gehele getal

## MathF::Round(float, int) methode

Rondt de opgegeven waarde af naar het dichtstbijzijnde getal met het opgegeven aantal cijfers achter de komma.

```cpp
static float System::MathF::Round(float value, int digits)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | **float** | De waarde die afgerond moet worden |
| digits | int | Het aantal cijfers achter de komma in de afgeronde waarde |

### Retourwaarde

Het getal met het opgegeven aantal cijfers dat het dichtst bij **value** ligt

## MathF::Round(float, MidpointRounding) methode

Rondt de opgegeven waarde af naar het dichtstbijzijnde gehele getal. Een parameter geeft het gedrag van de functie aan als de opgegeven waarde even ver van twee dichtstbijzijnde getallen ligt.

```cpp
static float System::MathF::Round(float value, MidpointRounding mode)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | **float** | De waarde die afgerond moet worden |
| mode | [MidpointRounding](../../midpointrounding/) | Geeft aan hoe de afronding uitgevoerd moet worden als **value** even ver van twee dichtstbijzijnde getallen ligt. |

### Retourwaarde

**value** afgerond naar het dichtstbijzijnde gehele getal

## MathF::Round(float, int, MidpointRounding) methode

Rondt de opgegeven waarde af naar het dichtstbijzijnde getal met het opgegeven aantal cijfers achter de komma. Een parameter geeft het gedrag van de functie aan als de opgegeven waarde even ver van twee dichtstbijzijnde getallen ligt.

```cpp
static float System::MathF::Round(float value, int digits, MidpointRounding mode)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | **float** | De waarde die afgerond moet worden |
| digits | int | Het aantal cijfers achter de komma in de afgeronde waarde |
| mode | [MidpointRounding](../../midpointrounding/) | Geeft aan hoe de afronding uitgevoerd moet worden als **value** even ver van twee dichtstbijzijnde getallen ligt. |

### Retourwaarde

Het getal met het opgegeven aantal cijfers dat het dichtst bij **value** ligt

## Zie ook

* Enum [MidpointRounding](../../midpointrounding/)
* Struct [MathF](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
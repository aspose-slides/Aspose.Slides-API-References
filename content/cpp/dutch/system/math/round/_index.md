---
title: Round()
second_title: Aspose.Slides voor C++ API-referentie
description: Rondt de opgegeven waarde af naar de dichtstbijzijnde gehele waarde.
type: docs
weight: 157
url: /nl/system/math/round/
---
## Math::Round(double) methode


Rondt de opgegeven waarde af naar de dichtstbijzijnde gehele waarde.

```cpp
static double System::Math::Round(double a)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | **double** | De waarde om af te ronden |

### Retourwaarde

**a** afgerond naar de dichtstbijzijnde gehele waarde

## Math::Round(double, int) methode


Rondt de opgegeven waarde af naar de dichtstbijzijnde waarde met het opgegeven aantal fractionele cijfers.

```cpp
static double System::Math::Round(double value, int digits)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | **double** | De waarde om af te ronden |
| digits | int | Het aantal fractionele cijfers in de afgeronde waarde |

### Retourwaarde

Het getal met het opgegeven aantal cijfers dat het dichtst bij **value** ligt

## Math::Round(double, MidpointRounding) methode


Rondt de opgegeven waarde af naar het dichtstbijzijnde gehele getal. Een parameter geeft het gedrag van de functie aan als de opgegeven waarde even dicht bij twee dichtstbijzijnde getallen ligt.

```cpp
static double System::Math::Round(double value, MidpointRounding mode)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | **double** | De waarde om af te ronden |
| mode | [MidpointRounding](../../midpointrounding/) | Geeft aan hoe het afronden moet worden uitgevoerd als **value** even dicht bij twee dichtstbijzijnde getallen ligt. |

### Retourwaarde

**value** afgerond naar het dichtstbijzijnde gehele getal

## Math::Round(double, int, MidpointRounding) methode


Rondt de opgegeven waarde af naar de dichtstbijzijnde waarde met het opgegeven aantal fractionele cijfers. Een parameter geeft het gedrag van de functie aan als de opgegeven waarde even dicht bij twee dichtstbijzijnde getallen ligt.

```cpp
static double System::Math::Round(double value, int digits, MidpointRounding mode)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | **double** | De waarde om af te ronden |
| digits | int | Het aantal fractionele cijfers in de afgeronde waarde |
| mode | [MidpointRounding](../../midpointrounding/) | Geeft aan hoe het afronden moet worden uitgevoerd als **value** even dicht bij twee dichtstbijzijnde getallen ligt. |

### Retourwaarde

Het getal met het opgegeven aantal cijfers dat het dichtst bij **value** ligt

## Math::Round(const Decimal\&) methode


Rondt de opgegeven waarde af naar het dichtstbijzijnde gehele getal.

```cpp
static Decimal System::Math::Round(const Decimal &d)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | De waarde om af te ronden |

### Retourwaarde

**d** afgerond naar het dichtstbijzijnde gehele getal

## Math::Round(const Decimal\&, int) methode


Rondt de opgegeven waarde af naar de dichtstbijzijnde waarde met het opgegeven aantal fractionele cijfers.

```cpp
static Decimal System::Math::Round(const Decimal &value, int digits)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | De waarde om af te ronden |
| digits | int | Het aantal fractionele cijfers in de afgeronde waarde |

### Retourwaarde

Het getal met het opgegeven aantal cijfers dat het dichtst bij **value** ligt

## Math::Round(const Decimal\&, MidpointRounding) methode


Rondt de opgegeven waarde af naar het dichtstbijzijnde gehele getal. Een parameter geeft het gedrag van de functie aan als de opgegeven waarde even dicht bij twee dichtstbijzijnde getallen ligt.

```cpp
static Decimal System::Math::Round(const Decimal &d, MidpointRounding mode)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | De waarde om af te ronden |
| mode | [MidpointRounding](../../midpointrounding/) | Geeft aan hoe het afronden moet worden uitgevoerd als **value** even dicht bij twee dichtstbijzijnde getallen ligt. |

### Retourwaarde

**d** afgerond naar het dichtstbijzijnde gehele getal

## Math::Round(const Decimal\&, int, MidpointRounding) methode


Rondt de opgegeven waarde af naar de dichtstbijzijnde waarde met het opgegeven aantal fractionele cijfers. Een parameter geeft het gedrag van de functie aan als de opgegeven waarde even dicht bij twee dichtstbijzijnde getallen ligt.

```cpp
static Decimal System::Math::Round(const Decimal &d, int digits, MidpointRounding mode)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | De waarde om af te ronden |
| digits | int | Het aantal fractionele cijfers in de afgeronde waarde |
| mode | [MidpointRounding](../../midpointrounding/) | Geeft aan hoe het afronden moet worden uitgevoerd als **value** even dicht bij twee dichtstbijzijnde getallen ligt. |

### Retourwaarde

Het getal met het opgegeven aantal cijfers dat het dichtst bij **value** ligt

## Zie ook

* Enum [MidpointRounding](../../midpointrounding/)
* Klasse [Decimal](../../decimal/)
* Struct [Math](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
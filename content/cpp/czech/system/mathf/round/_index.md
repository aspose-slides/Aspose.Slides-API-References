---
title: Round()
second_title: Aspose.Slides pro C++ API Reference
description: Zaokrouhlí zadanou hodnotu na nejbližší celočíselnou hodnotu.
type: docs
weight: 157
url: /cs/system/mathf/round/
---
## MathF::Round(float) metoda


Zaokrouhlí zadanou hodnotu na nejbližší celočíselnou hodnotu.

```cpp
static float System::MathF::Round(float a)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| a | **float** | Hodnota, která se má zaokrouhlit |

### Návratová hodnota

**a** zaokrouhlené na nejbližší celočíselnou hodnotu

## MathF::Round(float, int) metoda


Zaokrouhlí zadanou hodnotu na nejbližší hodnotu se zadaným počtem desetinných míst.

```cpp
static float System::MathF::Round(float value, int digits)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **float** | Hodnota, která se má zaokrouhlit |
| digits | int | Počet desetinných míst v zaokrouhlené hodnotě |

### Návratová hodnota

Číslo se zadaným počtem desetinných míst nejblíže **value**

## MathF::Round(float, MidpointRounding) metoda


Zaokrouhlí zadanou hodnotu na nejbližší celočíselné číslo. Parametr určuje chování funkce, pokud je zadaná hodnota stejně blízká dvěma nejbližším číslům.

```cpp
static float System::MathF::Round(float value, MidpointRounding mode)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **float** | Hodnota, která se má zaokrouhlit |
| mode | [MidpointRounding](../../midpointrounding/) | Určuje, jak provést zaokrouhlení, pokud je **value** stejně blízké dvěma nejbližším číslům. |

### Návratová hodnota

**value** zaokrouhlené na nejbližší celočíselnou hodnotu

## MathF::Round(float, int, MidpointRounding) metoda


Zaokrouhlí zadanou hodnotu na nejbližší hodnotu se zadaným počtem desetinných míst. Parametr určuje chování funkce, pokud je zadaná hodnota stejně blízká dvěma nejbližším číslům.

```cpp
static float System::MathF::Round(float value, int digits, MidpointRounding mode)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **float** | Hodnota, která se má zaokrouhlit |
| digits | int | Počet desetinných míst v zaokrouhlené hodnotě |
| mode | [MidpointRounding](../../midpointrounding/) | Určuje, jak provést zaokrouhlení, pokud je **value** stejně blízké dvěma nejbližším číslům. |

### Návratová hodnota

Číslo se zadaným počtem desetinných míst nejblíže **value**

## Viz také

* Výčet [MidpointRounding](../../midpointrounding/)
* Struktura [MathF](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)
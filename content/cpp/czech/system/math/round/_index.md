---
title: Round()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Zaokrouhlí zadanou hodnotu na nejbližší celou hodnotu.
type: docs
weight: 157
url: /cs/system/math/round/
---
## Math::Round(double) metoda


Zaokrouhlí zadanou hodnotu na nejbližší celou hodnotu.

```cpp
static double System::Math::Round(double a)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| a | **double** | Hodnota k zaokrouhlení |

### Návratová hodnota

**a** zaokrouhlená na nejbližší celou hodnotu

## Math::Round(double, int) metoda


Zaokrouhlí zadanou hodnotu na nejbližší hodnotu se zadaným počtem desetinných míst.

```cpp
static double System::Math::Round(double value, int digits)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **double** | Hodnota k zaokrouhlení |
| digits | int | Počet desetinných míst v zaokrouhlené hodnotě |

### Návratová hodnota

Číslo se zadaným počtem číslic nejbližší **value**

## Math::Round(double, MidpointRounding) metoda


Zaokrouhlí zadanou hodnotu na nejbližší celé číslo. Parametr určuje chování funkce, pokud je zadaná hodnota stejně blízká dvěma nejbližším číslům.

```cpp
static double System::Math::Round(double value, MidpointRounding mode)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **double** | Hodnota k zaokrouhlení |
| mode | [MidpointRounding](../../midpointrounding/) | Určuje, jak provést zaokrouhlování, pokud je **value** stejně blízká dvěma nejbližším číslům. |

### Návratová hodnota

**value** zaokrouhlená na nejbližší celou hodnotu

## Math::Round(double, int, MidpointRounding) metoda


Zaokrouhlí zadanou hodnotu na nejbližší hodnotu se zadaným počtem desetinných míst. Parametr určuje chování funkce, pokud je zadaná hodnota stejně blízká dvěma nejbližším číslům.

```cpp
static double System::Math::Round(double value, int digits, MidpointRounding mode)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **double** | Hodnota k zaokrouhlení |
| digits | int | Počet desetinných míst v zaokrouhlené hodnotě |
| mode | [MidpointRounding](../../midpointrounding/) | Určuje, jak provést zaokrouhlování, pokud je **value** stejně blízká dvěma nejbližším číslům. |

### Návratová hodnota

Číslo se zadaným počtem číslic nejbližší **value**

## Math::Round(const Decimal\&) metoda


Zaokrouhlí zadanou hodnotu na nejbližší celou hodnotu.

```cpp
static Decimal System::Math::Round(const Decimal &d)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | Hodnota k zaokrouhlení |

### Návratová hodnota

**d** zaokrouhlená na nejbližší celou hodnotu

## Math::Round(const Decimal\&, int) metoda


Zaokrouhlí zadanou hodnotu na nejbližší hodnotu se zadaným počtem desetinných míst.

```cpp
static Decimal System::Math::Round(const Decimal &value, int digits)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | Hodnota k zaokrouhlení |
| digits | int | Počet desetinných míst v zaokrouhlené hodnotě |

### Návratová hodnota

Číslo se zadaným počtem číslic nejbližší **value**

## Math::Round(const Decimal\&, MidpointRounding) metoda


Zaokrouhlí zadanou hodnotu na nejbližší celé číslo. Parametr určuje chování funkce, pokud je zadaná hodnota stejně blízká dvěma nejbližším číslům.

```cpp
static Decimal System::Math::Round(const Decimal &d, MidpointRounding mode)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | Hodnota k zaokrouhlení |
| mode | [MidpointRounding](../../midpointrounding/) | Určuje, jak provést zaokrouhlování, pokud je **value** stejně blízká dvěma nejbližším číslům. |

### Návratová hodnota

**d** zaokrouhlená na nejbližší celou hodnotu

## Math::Round(const Decimal\&, int, MidpointRounding) metoda


Zaokrouhlí zadanou hodnotu na nejbližší hodnotu se zadaným počtem desetinných míst. Parametr určuje chování funkce, pokud je zadaná hodnota stejně blízká dvěma nejbližším číslům.

```cpp
static Decimal System::Math::Round(const Decimal &d, int digits, MidpointRounding mode)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | Hodnota k zaokrouhlení |
| digits | int | Počet desetinných míst v zaokrouhlené hodnotě |
| mode | [MidpointRounding](../../midpointrounding/) | Určuje, jak provést zaokrouhlování, pokud je **value** stejně blízká dvěma nejbližším číslům. |

### Návratová hodnota

Číslo se zadaným počtem číslic nejbližší **value**

## Viz také

* Enum [MidpointRounding](../../midpointrounding/)
* Class [Decimal](../../decimal/)
* Struct [Math](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
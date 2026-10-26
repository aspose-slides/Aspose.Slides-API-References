---
title: Compare()
second_title: Aspose.Slides pro C++ API Reference
description: Porovnává dva podřetězce a určuje, zda je první menší, roven nebo větší než druhý.
type: docs
weight: 820
url: /cs/system/string/compare/
---
## String::Compare(const String\&, int, const String\&, int, int, bool) metoda


Porovnává dva podřetězce a vrací výsledek méně, rovno, více.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase=false)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| strA | const [String](../)\& | První řetězec k porovnání. |
| indexA | int | Počátek podřetězce prvního řetězce. |
| strB | const [String](../)\& | Druhý řetězec k porovnání. |
| indexB | int | Počátek podřetězce druhého řetězce. |
| length | int | Počet znaků k porovnání. |
| ignoreCase | **bool** | Určuje, zda je porovnání nezávislé na velikosti písmen. |

### Návratová hodnota

Negativní hodnota, pokud je první podřetězec menší než druhý, nula pokud se shodují, pozitivní hodnota v opačném případě.

## String::Compare(const String\&, int, const String\&, int, int, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) metoda


Porovnává dva podřetězce a vrací výsledek méně, rovno, více.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| strA | const [String](../)\& | První řetězec k porovnání. |
| indexA | int | Počátek podřetězce prvního řetězce. |
| strB | const [String](../)\& | Druhý řetězec k porovnání. |
| indexB | int | Počátek podřetězce druhého řetězce. |
| length | int | Počet znaků k porovnání. |
| ignoreCase | **bool** | Určuje, zda je porovnání nezávislé na velikosti písmen. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultura použita pro porovnání. |

### Návratová hodnota

Negativní hodnota, pokud je první podřetězec menší než druhý, nula pokud se shodují, pozitivní hodnota v opačném případě.

## String::Compare(const String\&, const String\&, System::StringComparison) metoda


Porovnává dva řetězce a vrací výsledek méně, rovno, více.

```cpp
static int System::String::Compare(const String &strA, const String &strB, System::StringComparison comparison_type)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| strA | const [String](../)\& | První řetězec k porovnání. |
| strB | const [String](../)\& | Druhý řetězec k porovnání. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) režim. |

### Návratová hodnota

Negativní hodnota, pokud je první podřetězec menší než druhý, nula pokud se shodují, pozitivní hodnota v opačném případě.

## String::Compare(const String\&, int, const String\&, int, int, System::StringComparison) metoda


Porovnává dva řetězce a vrací výsledek méně, rovno, více.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, System::StringComparison comparison_type)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| strA | const [String](../)\& | První řetězec k porovnání. |
| indexA | int | Počátek podřetězce prvního řetězce. |
| strB | const [String](../)\& | Druhý řetězec k porovnání. |
| indexB | int | Počátek podřetězce druhého řetězce. |
| length | int | Počet znaků k porovnání. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) režim. |

### Návratová hodnota

Negativní hodnota, pokud je první podřetězec menší než druhý, nula pokud se shodují, pozitivní hodnota v opačném případě.

## String::Compare(const String\&, const String\&, bool) metoda


Porovnává dva řetězce a vrací výsledek méně, rovno, více.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase=false)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| strA | const [String](../)\& | První řetězec k porovnání. |
| strB | const [String](../)\& | Druhý řetězec k porovnání. |
| ignoreCase | **bool** | Určuje, zda je porovnání nezávislé na velikosti písmen. |

### Návratová hodnota

Negativní hodnota, pokud je první podřetězec menší než druhý, nula pokud se shodují, pozitivní hodnota v opačném případě.

## String::Compare(const String\&, const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) metoda


Porovnává dva řetězce a vrací výsledek méně, rovno, více.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| strA | const [String](../)\& | První řetězec k porovnání. |
| strB | const [String](../)\& | Druhý řetězec k porovnání. |
| ignoreCase | **bool** | Určuje, zda je porovnání nezávislé na velikosti písmen. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultura použita pro porovnání. |

### Návratová hodnota

Negativní hodnota, pokud je první podřetězec menší než druhý, nula pokud se shodují, pozitivní hodnota v opačném případě.

## Viz také

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Třída [String](../)
* Třída [CultureInfo](../../../system.globalization/cultureinfo/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)
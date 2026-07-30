---
title: Equals()
second_title: Aspose.Slides pro C++ API Reference
description: Porovnání řetězců na rovnost. Je podporáno několik režimů poskytovaných výčtem StringComparison.
type: docs
weight: 391
url: /cs/system/string/equals/
---
## String::Equals(const String\&, System::StringComparison) const metoda

[String](../) porovnání na rovnost. Je podporáno několik režimů poskytovaných výčtem StringComparison.

```cpp
bool System::String::Equals(const String &str, System::StringComparison comparison_type) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) k porovnání s aktuálním. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) režim (viz [System::StringComparison](../../stringcomparison/) pro podrobnosti). |

### Návratová hodnota

true if strings match using selected comparison type, false otherwise.

## String::Equals(const String\&) const metoda

[String](../) porovnání na rovnost. Používá režim [System::StringComparison::Ordinal](../../stringcomparison/).

```cpp
bool System::String::Equals(const String &str) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) k porovnání s aktuálním. |

### Návratová hodnota

true if strings match, false otherwise.

## String::Equals(const String\&, const String\&) metoda

Porovnává dva řetězce pomocí režimu Ordial.

```cpp
static bool System::String::Equals(const String &strA, const String &strB)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| strA | const [String](../)\& | První řetězec k porovnání. |
| strB | const [String](../)\& | Druhý řetězec k porovnání. |

### Návratová hodnota

true if strings match, false otherwise.

## String::Equals(const String\&, const String\&, System::StringComparison) metoda

Porovnává dva řetězce.

```cpp
static bool System::String::Equals(const String &strA, const String &strB, System::StringComparison comparison_type)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| strA | const [String](../)\& | První řetězec k porovnání. |
| strB | const [String](../)\& | Druhý řetězec k porovnání. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) režim. |

### Návratová hodnota

true if strings match, false otherwise.

## Viz také

* Výčet [StringComparison](../../stringcomparison/)
* Třída [String](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)
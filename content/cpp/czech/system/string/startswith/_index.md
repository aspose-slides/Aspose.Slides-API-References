---
title: StartsWith()
second_title: Aspose.Slides pro C++ – reference API
description: Kontroluje, zda řetězec začíná zadaným podřetězcem.
type: docs
weight: 469
url: /cs/system/string/startswith/
---
## String::StartsWith(const String\&) const method

Kontroluje, zda řetězec začíná zadaným podřetězcem.

```cpp
bool System::String::StartsWith(const String &value) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../)\& | Vyhledávací řetězec. |

### Návratová hodnota

true pokud řetězec začíná zadaným podřetězcem, false v opačném případě.

## String::StartsWith(const String\&, System::StringComparison) const method

Kontroluje, zda řetězec začíná zadaným podřetězcem.

```cpp
bool System::String::StartsWith(const String &value, System::StringComparison comparisonType) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../)\& | Vyhledávací řetězec. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) režim, viz [System::StringComparison](../../stringcomparison/) pro podrobnosti. |

### Návratová hodnota

true pokud řetězec začíná zadaným podřetězcem, false v opačném případě.

## String::StartsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const method

Kontroluje, zda řetězec začíná zadaným podřetězcem.

```cpp
bool System::String::StartsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../)\& | Vyhledávací řetězec. |
| ignoreCase | **bool** | Určuje, zda je porovnání nerozlišující velikost písmen. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultura použitá při provádění porovnání řetězců. |

### Návratová hodnota

true pokud řetězec začíná zadaným podřetězcem, false v opačném případě.

## Viz také

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
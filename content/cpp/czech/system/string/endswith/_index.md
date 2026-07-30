---
title: EndsWith()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Kontroluje, zda řetězec končí zadaným podřetězcem.
type: docs
weight: 482
url: /cs/system/string/endswith/
---
## String::EndsWith(const String\&) const metoda

Kontroluje, zda řetězec končí zadaným podřetězcem.

```cpp
bool System::String::EndsWith(const String &value) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../)\& | Vyhledávaný řetězec. |

### Návratová hodnota

true, pokud řetězec končí zadaným podřetězcem, false jinak.

## String::EndsWith(const String\&, System::StringComparison) const metoda

Kontroluje, zda řetězec končí zadaným podřetězcem.

```cpp
bool System::String::EndsWith(const String &value, System::StringComparison comparisonType) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../)\& | Vyhledávaný řetězec. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) režim, viz [System::StringComparison](../../stringcomparison/) pro podrobnosti. |

### Návratová hodnota

true, pokud řetězec končí zadaným podřetězcem, false jinak.

## String::EndsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const metoda

Kontroluje, zda řetězec končí zadaným podřetězcem.

```cpp
bool System::String::EndsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../)\& | Vyhledávaný řetězec. |
| ignoreCase | **bool** | Určuje, zda je porovnání nezávislé na velikosti písmen. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultura, která se použije při provádění porovnání řetězců. |

### Návratová hodnota

true, pokud řetězec končí zadaným podřetězcem, false jinak.

## Viz také

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
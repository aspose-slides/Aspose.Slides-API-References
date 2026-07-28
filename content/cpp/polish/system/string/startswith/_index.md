---
title: StartsWith()
second_title: Odwołanie API Aspose.Slides dla C++
description: Sprawdza, czy ciąg zaczyna się od określonego podciągu.
type: docs
weight: 469
url: /pl/system/string/startswith/
---
## String::StartsWith(const String\&) const metoda


Sprawdza, czy ciąg zaczyna się od określonego podciągu.

```cpp
bool System::String::StartsWith(const String &value) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../)\& | Ciąg do wyszukania. |

### Wartość zwracana

true jeśli ciąg zaczyna się od określonego podciągu, false w przeciwnym razie.

## String::StartsWith(const String\&, System::StringComparison) const metoda


Sprawdza, czy ciąg zaczyna się od określonego podciągu.

```cpp
bool System::String::StartsWith(const String &value, System::StringComparison comparisonType) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../)\& | Ciąg do wyszukania. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) tryb, zobacz [System::StringComparison](../../stringcomparison/) po szczegóły. |

### Wartość zwracana

true jeśli ciąg zaczyna się od określonego podciągu, false w przeciwnym razie.

## String::StartsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const metoda


Sprawdza, czy ciąg zaczyna się od określonego podciągu.

```cpp
bool System::String::StartsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../)\& | Ciąg do wyszukania. |
| ignoreCase | **bool** | Określa, czy porównanie jest niewrażliwe na wielkość liter. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultura używana podczas porównywania ciągów. |

### Wartość zwracana

true jeśli ciąg zaczyna się od określonego podciągu, false w przeciwnym razie.

## Zobacz także

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasa [String](../)
* Klasa [CultureInfo](../../../system.globalization/cultureinfo/)
* Przestrzeń nazw [System](../../)
* Library [Aspose.Slides](../../../)
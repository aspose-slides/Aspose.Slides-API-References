---
title: Compare()
second_title: Aspose.Slides voor C++ API-referentie
description: Minder-gelijk-groter vergelijkt twee deelreeksen.
type: docs
weight: 820
url: /nl/system/string/compare/
---
## String::Compare(const String\&, int, const String\&, int, int, bool) methode


Minder-gelijk-groter vergelijkt twee deelreeksen.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase=false)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| strA | const [String](../)\& | Eerste string om te vergelijken. |
| indexA | int | Begin van de eerste string-deelreeks. |
| strB | const [String](../)\& | Tweede string om te vergelijken. |
| indexB | int | Begin van de tweede string-deelreeks. |
| length | int | Aantal tekens om te vergelijken. |
| ignoreCase | **bool** | Geeft aan of de vergelijking niet-hoofdlettergevoelig is. |

### Retourwaarde

Negatieve waarde als de eerste deelreeks kleiner is dan de tweede, nul als ze gelijk zijn, positieve waarde anders.

## String::Compare(const String\&, int, const String\&, int, int, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) methode


Minder-gelijk-groter vergelijkt twee deelreeksen.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| strA | const [String](../)\& | Eerste string om te vergelijken. |
| indexA | int | Begin van de eerste string-deelreeks. |
| strB | const [String](../)\& | Tweede string om te vergelijken. |
| indexB | int | Begin van de tweede string-deelreeks. |
| length | int | Aantal tekens om te vergelijken. |
| ignoreCase | **bool** | Geeft aan of de vergelijking niet-hoofdlettergevoelig is. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultuur die voor de vergelijking wordt gebruikt. |

### Retourwaarde

Negatieve waarde als de eerste deelreeks kleiner is dan de tweede, nul als ze gelijk zijn, positieve waarde anders.

## String::Compare(const String\&, const String\&, System::StringComparison) methode


Minder-gelijk-groter vergelijkt twee strings.

```cpp
static int System::String::Compare(const String &strA, const String &strB, System::StringComparison comparison_type)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| strA | const [String](../)\& | Eerste string om te vergelijken. |
| strB | const [String](../)\& | Tweede string om te vergelijken. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modus. |

### Retourwaarde

Negatieve waarde als de eerste deelreeks kleiner is dan de tweede, nul als ze gelijk zijn, positieve waarde anders.

## String::Compare(const String\&, int, const String\&, int, int, System::StringComparison) methode


Minder-gelijk-groter vergelijkt twee strings.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, System::StringComparison comparison_type)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| strA | const [String](../)\& | Eerste string om te vergelijken. |
| indexA | int | Begin van de eerste string-deelreeks. |
| strB | const [String](../)\& | Tweede string om te vergelijken. |
| indexB | int | Begin van de tweede string-deelreeks. |
| length | int | Aantal tekens om te vergelijken. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modus. |

### Retourwaarde

Negatieve waarde als de eerste deelreeks kleiner is dan de tweede, nul als ze gelijk zijn, positieve waarde anders.

## String::Compare(const String\&, const String\&, bool) methode


Minder-gelijk-groter vergelijkt twee strings.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase=false)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| strA | const [String](../)\& | Eerste string om te vergelijken. |
| strB | const [String](../)\& | Tweede string om te vergelijken. |
| ignoreCase | **bool** | Geeft aan of de vergelijking niet-hoofdlettergevoelig is. |

### Retourwaarde

Negatieve waarde als de eerste deelreeks kleiner is dan de tweede, nul als ze gelijk zijn, positieve waarde anders.

## String::Compare(const String\&, const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) methode


Minder-gelijk-groter vergelijkt twee strings.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| strA | const [String](../)\& | Eerste string om te vergelijken. |
| strB | const [String](../)\& | Tweede string om te vergelijken. |
| ignoreCase | **bool** | Geeft aan of de vergelijking niet-hoofdlettergevoelig is. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultuur die voor de vergelijking wordt gebruikt. |

### Retourwaarde

Negatieve waarde als de eerste deelreeks kleiner is dan de tweede, nul als ze gelijk zijn, positieve waarde anders.

## Zie ook

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Naamruimte [System](../../)
* Library [Aspose.Slides](../../../)
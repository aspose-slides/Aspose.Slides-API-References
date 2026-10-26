---
title: StartsWith()
second_title: Aspose.Slides voor C++ API-referentie
description: Controleert of de tekenreeks begint met de opgegeven subreeks.
type: docs
weight: 469
url: /nl/system/string/startswith/
---
## String::StartsWith(const String\&) const method

Controleert of de tekenreeks begint met de opgegeven subreeks.

```cpp
bool System::String::StartsWith(const String &value) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../)\& | Zoektekenreeks. |

### Retourwaarde

true als de tekenreeks begint met de opgegeven subreeks, false anders.

## String::StartsWith(const String\&, System::StringComparison) const method

Controleert of de tekenreeks begint met de opgegeven subreeks.

```cpp
bool System::String::StartsWith(const String &value, System::StringComparison comparisonType) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../)\& | Zoektekenreeks. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/)-modus, zie [System::StringComparison](../../stringcomparison/) voor details. |

### Retourwaarde

true als de tekenreeks begint met de opgegeven subreeks, false anders.

## String::StartsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const method

Controleert of de tekenreeks begint met de opgegeven subreeks.

```cpp
bool System::String::StartsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../)\& | Zoektekenreeks. |
| ignoreCase | **bool** | Specificeert of de vergelijking hoofdletterongevoelig is. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Culture die wordt gebruikt bij het uitvoeren van de tekenreeksvergelijking. |

### Retourwaarde

true als de tekenreeks begint met de opgegeven subreeks, false anders.

## Zie ook

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)
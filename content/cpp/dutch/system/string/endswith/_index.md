---
title: EndsWith()
second_title: Aspose.Slides voor C++ API-referentie
description: Controleert of een tekenreeks eindigt met een opgegeven subtekenreeks.
type: docs
weight: 482
url: /nl/system/string/endswith/
---
## String::EndsWith(const String\&) const methode

Controleert of de tekenreeks eindigt met de opgegeven subtekenreeks.

```cpp
bool System::String::EndsWith(const String &value) const
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | Zoektekenreeks. |

### Return Value

true als de tekenreeks eindigt met de opgegeven subtekenreeks, anders false.

## String::EndsWith(const String\&, System::StringComparison) const methode

Controleert of de tekenreeks eindigt met de opgegeven subtekenreeks.

```cpp
bool System::String::EndsWith(const String &value, System::StringComparison comparisonType) const
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | Zoektekenreeks. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modus, zie [System::StringComparison](../../stringcomparison/) voor details. |

### Return Value

true als de tekenreeks eindigt met de opgegeven subtekenreeks, anders false.

## String::EndsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const methode

Controleert of de tekenreeks eindigt met de opgegeven subtekenreeks.

```cpp
bool System::String::EndsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | Zoektekenreeks. |
| ignoreCase | **bool** | Geeft aan of de vergelijking hoofdletterongevoelig is. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultuur die gebruikt wordt bij het uitvoeren van de tekenreeksvergelijking. |

### Return Value

true als de tekenreeks eindigt met de opgegeven subtekenreeks, anders false.

## Zie Ook

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
---
title: StartsWith()
second_title: Aspose.Slides für C++ API-Referenz
description: Überprüft, ob die Zeichenfolge mit dem angegebenen Teilstring beginnt.
type: docs
weight: 469
url: /de/system/string/startswith/
---
## String::StartsWith(const String\&) const Methode

Überprüft, ob die Zeichenfolge mit dem angegebenen Teilstring beginnt.

```cpp
bool System::String::StartsWith(const String &value) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../)\& | Suchzeichenfolge. |

### Rückgabewert

true, wenn die Zeichenfolge mit dem angegebenen Teilstring beginnt, andernfalls false.

## String::StartsWith(const String\&, System::StringComparison) const Methode

Überprüft, ob die Zeichenfolge mit dem angegebenen Teilstring beginnt.

```cpp
bool System::String::StartsWith(const String &value, System::StringComparison comparisonType) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../)\& | Suchzeichenfolge. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) Modus, siehe [System::StringComparison](../../stringcomparison/) für Details. |

### Rückgabewert

true, wenn die Zeichenfolge mit dem angegebenen Teilstring beginnt, andernfalls false.

## String::StartsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const Methode

Überprüft, ob die Zeichenfolge mit dem angegebenen Teilstring beginnt.

```cpp
bool System::String::StartsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../)\& | Suchzeichenfolge. |
| ignoreCase | **bool** | Gibt an, ob der Vergleich die Groß-/Kleinschreibung ignoriert. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultur, die beim Durchführen des Zeichenfolgenvergleichs verwendet wird. |

### Rückgabewert

true, wenn die Zeichenfolge mit dem angegebenen Teilstring beginnt, andernfalls false.

## Siehe auch

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Namensraum [System](../../)
* Library [Aspose.Slides](../../../)
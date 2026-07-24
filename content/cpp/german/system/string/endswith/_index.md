---
title: EndsWith()
second_title: Aspose.Slides für C++ API-Referenz
description: Prüft, ob die Zeichenkette mit dem angegebenen Teilstring endet.
type: docs
weight: 482
url: /de/system/string/endswith/
---
## String::EndsWith(const String\&) const method


Überprüft, ob die Zeichenkette mit dem angegebenen Teilstring endet.

```cpp
bool System::String::EndsWith(const String &value) const
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../)\& | Nachschlagezeichenkette. |

### Rückgabewert

Wahr, wenn die Zeichenkette mit dem angegebenen Teilstring endet, sonst falsch.

## String::EndsWith(const String\&, System::StringComparison) const method


Überprüft, ob die Zeichenkette mit dem angegebenen Teilstring endet.

```cpp
bool System::String::EndsWith(const String &value, System::StringComparison comparisonType) const
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../)\& | Nachschlagezeichenkette. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) Modus, siehe [System::StringComparison](../../stringcomparison/) für Details. |

### Rückgabewert

Wahr, wenn die Zeichenkette mit dem angegebenen Teilstring endet, sonst falsch.

## String::EndsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const method


Überprüft, ob die Zeichenkette mit dem angegebenen Teilstring endet.

```cpp
bool System::String::EndsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../)\& | Nachschlagezeichenkette. |
| ignoreCase | **bool** | Gibt an, ob der Vergleich Groß- und Kleinschreibung ignoriert. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultur, die bei der Durchführung des String-Vergleichs verwendet wird. |

### Rückgabewert

Wahr, wenn die Zeichenkette mit dem angegebenen Teilstring endet, sonst falsch.

## Siehe auch

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
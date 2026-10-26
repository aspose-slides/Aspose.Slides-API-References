---
title: Compare()
second_title: Aspose.Slides für C++ API-Referenz
description: Vergleicht zwei Teilzeichenketten nach dem Prinzip kleiner-gleich-größer.
type: docs
weight: 820
url: /de/system/string/compare/
---
## String::Compare(const String\&, int, const String\&, int, int, bool) Methode


Vergleicht zwei Teilzeichenketten nach dem Prinzip kleiner-gleich-größer.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase=false)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| strA | const [String](../)\& | Erste Zeichenkette zum Vergleichen. |
| indexA | int | Anfang der ersten Teilzeichenkette. |
| strB | const [String](../)\& | Zweite Zeichenkette zum Vergleichen. |
| indexB | int | Anfang der zweiten Teilzeichenkette. |
| length | int | Anzahl der zu vergleichenden Zeichen. |
| ignoreCase | **bool** | Gibt an, ob der Vergleich ohne Berücksichtigung der Groß- und Kleinschreibung durchgeführt wird. |

### Rückgabewert

Negativer Wert, wenn die erste Teilzeichenkette kleiner als die zweite ist, Null, wenn sie übereinstimmen, sonst ein positiver Wert.

## String::Compare(const String\&, int, const String\&, int, int, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) Methode


Vergleicht zwei Teilzeichenketten nach dem Prinzip kleiner-gleich-größer.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| strA | const [String](../)\& | Erste Zeichenkette zum Vergleichen. |
| indexA | int | Anfang der ersten Teilzeichenkette. |
| strB | const [String](../)\& | Zweite Zeichenkette zum Vergleichen. |
| indexB | int | Anfang der zweiten Teilzeichenkette. |
| length | int | Anzahl der zu vergleichenden Zeichen. |
| ignoreCase | **bool** | Gibt an, ob der Vergleich ohne Berücksichtigung der Groß- und Kleinschreibung durchgeführt wird. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Für den Vergleich zu verwendende Kultur. |

### Rückgabewert

Negativer Wert, wenn die erste Teilzeichenkette kleiner als die zweite ist, Null, wenn sie übereinstimmen, sonst ein positiver Wert.

## String::Compare(const String\&, const String\&, System::StringComparison) Methode


Vergleicht zwei Zeichenketten nach dem Prinzip kleiner-gleich-größer.

```cpp
static int System::String::Compare(const String &strA, const String &strB, System::StringComparison comparison_type)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| strA | const [String](../)\& | Erste Zeichenkette zum Vergleichen. |
| strB | const [String](../)\& | Zweite Zeichenkette zum Vergleichen. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) Modus. |

### Rückgabewert

Negativer Wert, wenn die erste Teilzeichenkette kleiner als die zweite ist, Null, wenn sie übereinstimmen, sonst ein positiver Wert.

## String::Compare(const String\&, int, const String\&, int, int, System::StringComparison) Methode


Vergleicht zwei Zeichenketten nach dem Prinzip kleiner-gleich-größer.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, System::StringComparison comparison_type)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| strA | const [String](../)\& | Erste Zeichenkette zum Vergleichen. |
| indexA | int | Anfang der ersten Teilzeichenkette. |
| strB | const [String](../)\& | Zweite Zeichenkette zum Vergleichen. |
| indexB | int | Anfang der zweiten Teilzeichenkette. |
| length | int | Anzahl der zu vergleichenden Zeichen. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) Modus. |

### Rückgabewert

Negativer Wert, wenn die erste Teilzeichenkette kleiner als die zweite ist, Null, wenn sie übereinstimmen, sonst ein positiver Wert.

## String::Compare(const String\&, const String\&, bool) Methode


Vergleicht zwei Zeichenketten nach dem Prinzip kleiner-gleich-größer.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase=false)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| strA | const [String](../)\& | Erste Zeichenkette zum Vergleichen. |
| strB | const [String](../)\& | Zweite Zeichenkette zum Vergleichen. |
| ignoreCase | **bool** | Gibt an, ob der Vergleich ohne Berücksichtigung der Groß- und Kleinschreibung durchgeführt wird. |

### Rückgabewert

Negativer Wert, wenn die erste Teilzeichenkette kleiner als die zweite ist, Null, wenn sie übereinstimmen, sonst ein positiver Wert.

## String::Compare(const String\&, const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) Methode


Vergleicht zwei Zeichenketten nach dem Prinzip kleiner-gleich-größer.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| strA | const [String](../)\& | Erste Zeichenkette zum Vergleichen. |
| strB | const [String](../)\& | Zweite Zeichenkette zum Vergleichen. |
| ignoreCase | **bool** | Gibt an, ob der Vergleich ohne Berücksichtigung der Groß- und Kleinschreibung durchgeführt wird. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Für den Vergleich zu verwendende Kultur. |

### Rückgabewert

Negativer Wert, wenn die erste Teilzeichenkette kleiner als die zweite ist, Null, wenn sie übereinstimmen, sonst ein positiver Wert.

## Siehe auch

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Namensraum [System](../../)
* Library [Aspose.Slides](../../../)
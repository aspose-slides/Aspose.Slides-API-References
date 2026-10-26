---
title: Parse()
second_title: Aspose.Slides für C++ API Referenz
description: Konvertiert die Zeichenkettenrepräsentation einer Dezimalzahl in eine gleichwertige Instanz der Klasse Decimal.
type: docs
weight: 469
url: /de/system/decimal/parse/
---
## Decimal::Parse(const String\&) method

Konvertiert die Zeichenkettenrepräsentation einer Dezimalzahl in eine gleichwertige Instanz der Klasse [Decimal](../).

```cpp
static Decimal System::Decimal::Parse(const String &s)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | const [String](../../string/)\& | Die Zeichenkettenrepräsentation einer Zahl |

### Rückgabewert

Eine neue Instanz der Klasse [Decimal](../), die einen Wert repräsentiert, der dem durch die angegebene Zeichenkette dargestellten Wert entspricht.

## Decimal::Parse(const String\&, Globalization::NumberStyles) method

Konvertiert die Zeichenkettenrepräsentation einer Dezimalzahl in eine gleichwertige Instanz der Klasse [Decimal](../) unter Verwendung des angegebenen Stils.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | const [String](../../string/)\& | Die Zeichenkettenrepräsentation eines Dezimalwerts, der konvertiert werden soll |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Eine bitweise Kombination der Aufzählungswerte, die zusätzliche Informationen über **s**, über Stilelemente, die in **s** vorhanden sein können, oder über die Umwandlung von **s** in ein [Decimal](../)-Objekt bereitstellt |

### Rückgabewert

Eine neue Instanz der Klasse [Decimal](../), die einen Wert repräsentiert, der dem durch die angegebene Zeichenkette dargestellten Wert entspricht.

## Decimal::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) method

Konvertiert die Zeichenkettenrepräsentation einer Dezimalzahl in eine gleichwertige Instanz der Klasse [Decimal](../) unter Verwendung des angegebenen Formatproviders.

```cpp
static Decimal System::Decimal::Parse(const String &s, const SharedPtr<IFormatProvider> &provider)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | const [String](../../string/)\& | Die Zeichenkettenrepräsentation eines Dezimalwerts, der konvertiert werden soll |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formatprovider |

### Rückgabewert

Eine neue Instanz der Klasse [Decimal](../), die einen Wert repräsentiert, der dem durch die angegebene Zeichenkette dargestellten Wert entspricht.

## Decimal::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) method

Konvertiert die Zeichenkettenrepräsentation einer Dezimalzahl in eine gleichwertige Instanz der Klasse [Decimal](../) unter Verwendung des angegebenen Stils und des Formatproviders.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | const [String](../../string/)\& | Die Zeichenkettenrepräsentation eines Dezimalwerts, der konvertiert werden soll |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Eine bitweise Kombination der Aufzählungswerte, die zusätzliche Informationen über **s**, über Stilelemente, die in **s** vorhanden sein können, oder über die Umwandlung von **s** in ein [Decimal](../)-Objekt bereitstellt |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formatprovider |

### Rückgabewert

Eine neue Instanz der Klasse [Decimal](../), die einen Wert repräsentiert, der dem durch die angegebene Zeichenkette dargestellten Wert entspricht.

## Siehe auch

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Decimal](../)
* Klasse [String](../../string/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Namensraum [System](../../)
* Library [Aspose.Slides](../../../)
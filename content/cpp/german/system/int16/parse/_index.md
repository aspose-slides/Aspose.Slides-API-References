---
title: Parse()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert die angegebene Zeichenkette, die die String-Darstellung einer Zahl enthält, in die entsprechende 16-Bit-vorzeichenbehaftete ganze Zahl.
type: docs
weight: 1
url: /de/system/int16/parse/
---
## Int16::Parse(const String\&) Methode

Konvertiert die angegebene Zeichenkette, die die String-Darstellung einer Zahl enthält, in die entsprechende 16-Bit-vorzeichenbehaftete ganze Zahl.

```cpp
static int16_t System::Int16::Parse(const String &value)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert. |

### Rückgabewert

Die 16-Bit-vorzeichenbehaftete ganze Zahl, die der durch die angegebene Zeichenkette dargestellten Zahl entspricht.

## Int16::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) Methode

Konvertiert die angegebene Zeichenkette, die die String-Darstellung einer Zahl enthält, in die entsprechende 16-Bit-vorzeichenbehaftete ganze Zahl unter Verwendung der bereitgestellten Formatierungsinformationen.

```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Zeichenkettenformatierungsinformationen enthält. |

### Rückgabewert

Die 16-Bit-vorzeichenbehaftete ganze Zahl, die der durch die angegebene Zeichenkette dargestellten Zahl entspricht.

## Int16::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) Methode

```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int16::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) Methode

```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int16::Parse(const String\&, std::nullptr_t) Methode

```cpp
static int16_t System::Int16::Parse(const String &value, std::nullptr_t)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) Methode

Konvertiert die angegebene Zeichenkette, die die String-Darstellung einer Zahl enthält, in die entsprechende 16-Bit-vorzeichenbehaftete ganze Zahl unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils.

```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Eine bitweise Kombination von Werten des NumberStyles-Enums, die den zulässigen Stil der Zeichenketten-Darstellung einer Zahl spezifiziert. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Zeichenkettenformatierungsinformationen enthält. |

### Rückgabewert

Die 16-Bit-vorzeichenbehaftete ganze Zahl, die der durch die angegebene Zeichenkette dargestellten Zahl entspricht.

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) Methode

```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) Methode

```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) Methode

```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Siehe auch

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [Int16](../)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namensraum [System](../../)
* Library [Aspose.Slides](../../../)
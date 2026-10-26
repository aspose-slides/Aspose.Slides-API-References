---
title: Parse()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert die angegebene Zeichenfolge, die die Zeichenkettenrepräsentation einer Zahl enthält, in die entsprechende 32-Bit vorzeichenlose Ganzzahl.
type: docs
weight: 1
url: /de/system/uint32/parse/
---
## UInt32::Parse(const String\&) Methode

Konvertiert die angegebene Zeichenfolge, die die Zeichenkettenrepräsentation einer Zahl enthält, in die entsprechende 32-Bit-vorzeichenlose Ganzzahl.

```cpp
static uint32_t System::UInt32::Parse(const String &value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenfolge. |

### Rückgabewert

Die 32-Bit-vorzeichenlose Ganzzahl, die der durch die angegebene Zeichenfolge dargestellten Zahl entspricht.

## UInt32::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) Methode

Konvertiert die angegebene Zeichenfolge, die die Zeichenkettenrepräsentation einer Zahl enthält, in die entsprechende 32-Bit-vorzeichenlose Ganzzahl unter Verwendung der bereitgestellten Formatierungsinformationen.

```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenfolge. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Zeichenkettenformatinformationen enthält. |

### Rückgabewert

Die 32-Bit-vorzeichenlose Ganzzahl, die der durch die angegebene Zeichenfolge dargestellten Zahl entspricht.

## UInt32::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) Methode




```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt32::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) Methode




```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt32::Parse(const String\&, std::nullptr_t) Methode




```cpp
static uint32_t System::UInt32::Parse(const String &value, std::nullptr_t)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) Methode

Konvertiert die angegebene Zeichenfolge, die die Zeichenkettenrepräsentation einer Zahl enthält, in die entsprechende 32-Bit-vorzeichenlose Ganzzahl unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils.

```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenfolge. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Eine bitweise Kombination von Werten des NumberStyles-Enums, die den zulässigen Stil der Zeichenkettenrepräsentation einer Zahl angibt. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Zeichenkettenformatinformationen enthält. |

### Rückgabewert

Die 32-Bit-vorzeichenlose Ganzzahl, die der durch die angegebene Zeichenfolge dargestellten Zahl entspricht.

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) Methode




```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) Methode




```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) Methode




```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Siehe auch

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt32](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
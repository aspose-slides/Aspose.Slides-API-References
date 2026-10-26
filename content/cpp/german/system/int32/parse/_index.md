---
title: Parse()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert die angegebene Zeichenfolge, die die Zeichenkettenrepräsentation einer Zahl enthält, in die entsprechende vorzeichenbehaftete 32-bit Ganzzahl.
type: docs
weight: 1
url: /de/system/int32/parse/
---
## Int32::Parse(const String\&) Methode

Konvertiert die angegebene Zeichenfolge, die die Zeichenkettenrepräsentation einer Zahl enthält, in die entsprechende vorzeichenbehaftete 32-bit Ganzzahl.

```cpp
static int32_t System::Int32::Parse(const String &value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenfolge. |

### Rückgabewert

Die vorzeichenbehaftete 32-bit Ganzzahl, die der durch die angegebene Zeichenfolge dargestellten Zahl entspricht.

## Int32::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) Methode

Konvertiert die angegebene Zeichenfolge, die die Zeichenkettenrepräsentation einer Zahl enthält, in die entsprechende vorzeichenbehaftete 32-bit Ganzzahl unter Verwendung der bereitgestellten Formatierungsinformationen.

```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenfolge. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Zeichenkettenformatinformationen enthält. |

### Rückgabewert

Die vorzeichenbehaftete 32-bit Ganzzahl, die der durch die angegebene Zeichenfolge dargestellten Zahl entspricht.

## Int32::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) Methode

```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int32::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) Methode

```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int32::Parse(const String\&, std::nullptr_t) Methode

```cpp
static int32_t System::Int32::Parse(const String &value, std::nullptr_t)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) Methode

Konvertiert die angegebene Zeichenfolge, die die Zeichenkettenrepräsentation einer Zahl enthält, in die entsprechende vorzeichenbehaftete 32-bit Ganzzahl unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils.

```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenfolge. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Eine bitweise Kombination von Werten des Enums NumberStyles, die den zulässigen Stil der Zeichenkettenrepräsentation einer Zahl angibt. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Zeichenkettenformatinformationen enthält. |

### Rückgabewert

Die vorzeichenbehaftete 32-bit Ganzzahl, die der durch die angegebene Zeichenfolge dargestellten Zahl entspricht.

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) Methode

```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) Methode

```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) Methode

```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&) Methode

```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&, std::nullptr_t) Methode

```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span, std::nullptr_t)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) Methode

```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

## Siehe auch

* Aufzählung [NumberStyles](../../../system.globalization/numberstyles/)
* Typdefinition [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [Int32](../)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Klasse [ReadOnlySpan](../../readonlyspan/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)
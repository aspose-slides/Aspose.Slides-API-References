---
title: Parse()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert die angegebene Zeichenfolge, die die Stringdarstellung einer Zahl enthält, in die entsprechende 64-bit vorzeichenbehaftete Ganzzahl.
type: docs
weight: 1
url: /de/system/int64/parse/
---
## Int64::Parse(const String\&) Methode


Konvertiert die angegebene Zeichenfolge, die die Stringdarstellung einer Zahl enthält, in die entsprechende 64-Bit vorzeichenbehaftete Ganzzahl.

```cpp
static int64_t System::Int64::Parse(const String &value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenfolge. |

### Rückgabewert

Die 64-Bit vorzeichenbehaftete Ganzzahl, die der durch die angegebene Zeichenfolge dargestellten Zahl entspricht.

## Int64::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) Methode


Konvertiert die angegebene Zeichenfolge, die die Stringdarstellung einer Zahl enthält, in die entsprechende 64-Bit vorzeichenbehaftete Ganzzahl unter Verwendung der bereitgestellten Formatierungsinformationen.

```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenfolge. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Informationen zum Zeichenfolgenformat enthält. |

### Rückgabewert

Die 64-Bit vorzeichenbehaftete Ganzzahl, die der durch die angegebene Zeichenfolge dargestellten Zahl entspricht.

## Int64::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) Methode




```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int64::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) Methode




```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int64::Parse(const String\&, std::nullptr_t) Methode




```cpp
static int64_t System::Int64::Parse(const String &value, std::nullptr_t)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) Methode


Konvertiert die angegebene Zeichenfolge, die die Stringdarstellung einer Zahl enthält, in die entsprechende 64-Bit vorzeichenbehaftete Ganzzahl unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils.

```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenfolge. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Eine bitweise Kombination von Werten des Enums NumberStyles, die den zulässigen Stil der Zeichenfolgendarstellung einer Zahl angibt. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Informationen zum Zeichenfolgenformat enthält. |

### Rückgabewert

Die 64-Bit vorzeichenbehaftete Ganzzahl, die der durch die angegebene Zeichenfolge dargestellten Zahl entspricht.

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) Methode 




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) Methode 




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) Methode 




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Siehe auch

* Aufzählung [NumberStyles](../../../system.globalization/numberstyles/)
* Typdefinition [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [Int64](../)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)
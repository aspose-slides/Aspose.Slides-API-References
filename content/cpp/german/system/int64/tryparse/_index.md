---
title: TryParse()
second_title: Aspose.Slides für C++ API Referenz
description: Konvertiert die angegebene Zeichenfolge, die die Zeichenkettenrepräsentation einer Zahl enthält, in die entsprechende vorzeichenbehaftete 64-bit Ganzzahl.
type: docs
weight: 14
url: /de/system/int64/tryparse/
---
## Int64::TryParse(const String\&, int64_t\&) Methode


Konvertiert die angegebene Zeichenfolge, die die Zeichenkettenrepräsentation einer Zahl enthält, in die entsprechende vorzeichenbehaftete 64-Bit-Ganzzahl.

```cpp
static bool System::Int64::TryParse(const String &value, int64_t &result)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenfolge. |
| result | **int64_t**\& | Die Referenz auf eine vorzeichenbehaftete 64-Bit-Ganzzahlvariable, in die das Ergebnis der Konvertierung geschrieben wird. |

### Rückgabewert

True, wenn die Konvertierung erfolgreich war, sonst - false.

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int64_t\&) Methode


Konvertiert die angegebene Zeichenfolge, die die Zeichenkettenrepräsentation einer Zahl enthält, in die entsprechende vorzeichenbehaftete 64-Bit-Ganzzahl unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils.

```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int64_t &result)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenfolge. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Eine bitweise Kombination von Werten des NumberStyles-Enums, die den zulässigen Stil der Zeichenkettenrepräsentation einer Zahl angibt. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Zeichenkettenformatinformationen enthält. |
| result | **int64_t**\& | Die Referenz auf eine vorzeichenbehaftete 64-Bit-Ganzzahlvariable, in die das Ergebnis der Konvertierung geschrieben wird. |

### Rückgabewert

True, wenn die Konvertierung erfolgreich war, sonst - false.

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int64_t\&) Methode




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int64_t &result)
```

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int64_t\&) Methode




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int64_t &result)
```

## Int64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int64_t\&) Methode




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int64_t &result)
```

## Siehe auch

* Aufzählung [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [Int64](../)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)
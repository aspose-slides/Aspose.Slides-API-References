---
title: TryParse()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert die angegebene Zeichenkette, die die Zeichenkettenrepräsentation einer Zahl enthält, in die entsprechende 32-bit-Unsigned-Integer-Zahl.
type: docs
weight: 14
url: /de/system/uint32/tryparse/
---
## UInt32::TryParse(const String\&, uint32_t\&) method


Konvertiert die angegebene Zeichenkette, die die Zeichenkettenrepräsentation einer Zahl enthält, in die entsprechende 32-Bit-Unsigned-Integer-Zahl.

```cpp
static bool System::UInt32::TryParse(const String &value, uint32_t &result)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette. |
| result | **uint32_t**\& | Die Referenz auf eine 32-Bit-Unsigned-Integer-Variable, in die das Ergebnis der Konvertierung geschrieben wird. |

### Rückgabewert

True wenn die Konvertierung erfolgreich war, andernfalls - false.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint32_t\&) method


Konvertiert die angegebene Zeichenkette, die die Zeichenkettenrepräsentation einer Zahl enthält, in die entsprechende 32-Bit-Unsigned-Integer-Zahl unter Verwendung der angegebenen Formatierungsinformationen und des Zahlenstils.

```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint32_t &result)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Eine Bitwise-Kombination von Werten des NumberStyles-Enums, die den zulässigen Stil der Zeichenkettenrepräsentation einer Zahl angibt. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Zeichenkettenformatinformationen enthält. |
| result | **uint32_t**\& | Die Referenz auf eine 32-Bit-Unsigned-Integer-Variable, in die das Ergebnis der Konvertierung geschrieben wird. |

### Rückgabewert

True wenn die Konvertierung erfolgreich war, andernfalls - false.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint32_t\&) method




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint32_t\&) method




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint32_t\&) method




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint32_t &result)
```

## Siehe auch

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struktur [UInt32](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)
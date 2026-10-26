---
title: TryParse()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert die angegebene Zeichenfolge, die die Zeichenkettenrepräsentation einer Zahl enthält, in das entsprechende 16-Bit-vorzeichenlose Integer.
type: docs
weight: 14
url: /de/system/uint16/tryparse/
---
## UInt16::TryParse(const String\&, uint16_t\&) Methode

Konvertiert die angegebene Zeichenfolge, die die Zeichenkettenrepräsentation einer Zahl enthält, in das entsprechende 16-Bit-vorzeichenlose Integer.

```cpp
static bool System::UInt16::TryParse(const String &value, uint16_t &result)
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenfolge. |
| result | **uint16_t**\& | Die Referenz auf eine 16-Bit-vorzeichenlose Integer-Variable, in die das Ergebnis der Konvertierung geschrieben wird. |

### Rückgabewert

True if the conversion succeeded, otherwise - false.

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint16_t\&) Methode

Konvertiert die angegebene Zeichenfolge, die die Zeichenkettenrepräsentation einer Zahl enthält, in das entsprechende 16-Bit-vorzeichenlose Integer unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils.

```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint16_t &result)
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenfolge. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Eine bitweise Kombination von Werten des NumberStyles-Enums, die den zulässigen Stil der Zeichenkettenrepräsentation einer Zahl angibt. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Zeichenfolgenformatinformationen enthält. |
| result | **uint16_t**\& | Die Referenz auf eine 16-Bit-vorzeichenlose Integer-Variable, in die das Ergebnis der Konvertierung geschrieben wird. |

### Rückgabewert

True if the conversion succeeded, otherwise - false.

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint16_t\&) Methode




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint16_t\&) Methode




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint16_t\&) Methode




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint16_t &result)
```

## Siehe auch

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt16](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
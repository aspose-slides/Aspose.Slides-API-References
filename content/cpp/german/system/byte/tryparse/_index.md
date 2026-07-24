---
title: TryParse()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert die angegebene Zeichenkette, die die Zeichenkettenrepräsentation einer Zahl enthält, in das entsprechende 8-Bit-vorzeichenlose Integer.
type: docs
weight: 14
url: /de/system/byte/tryparse/
---
## Byte::TryParse(const String\&, uint8_t\&) Methode

Konvertiert die angegebene Zeichenkette, die die Zeichenkettenrepräsentation einer Zahl enthält, in das entsprechende 8-Bit-vorzeichenlose Integer.

```cpp
static bool System::Byte::TryParse(const String &value, uint8_t &result)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette. |
| result | **uint8_t**\& | Die Referenz auf eine 8-Bit-vorzeichenlose Integer-Variable, in die das Ergebnis der Konvertierung geschrieben wird. |

### Rückgabewert

Wahr, wenn die Konvertierung erfolgreich war, sonst - falsch.

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint8_t\&) Methode

Konvertiert die angegebene Zeichenkette, die die Zeichenkettenrepräsentation einer Zahl enthält, in das entsprechende 8-Bit-vorzeichenlose Integer unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils.

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint8_t &result)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Eine bitweise Kombination von Werten des NumberStyles-Enums, die den zulässigen Stil der Zeichenkettenrepräsentation einer Zahl angibt. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Zeichenkettenformatinformationen enthält. |
| result | **uint8_t**\& | Die Referenz auf eine 8-Bit-vorzeichenlose Integer-Variable, in die das Ergebnis der Konvertierung geschrieben wird. |

### Rückgabewert

Wahr, wenn die Konvertierung erfolgreich war, sonst - falsch.

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint8_t\&) Methode




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint8_t\&) Methode




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint8_t\&) Methode




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint8_t &result)
```

## Siehe auch

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [Byte](../)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)
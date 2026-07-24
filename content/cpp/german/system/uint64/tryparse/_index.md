---
title: TryParse()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert die angegebene Zeichenkette, die die Zeichenfolgendarstellung einer Zahl enthält, in die entsprechende 64-bit Ganzzahl ohne Vorzeichen.
type: docs
weight: 14
url: /de/system/uint64/tryparse/
---
## UInt64::TryParse(const String\&, uint64_t\&) Methode

Konvertiert die angegebene Zeichenkette, die die Zeichenfolgendarstellung einer Zahl enthält, in die entsprechende 64-Bit-Ganzzahl ohne Vorzeichen.

```cpp
static bool System::UInt64::TryParse(const String &value, uint64_t &result)
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Der zu konvertierende String. |
| result | **uint64_t**\& | Die Referenz auf eine 64-Bit-Ganzzahl-Variable ohne Vorzeichen, in die das Ergebnis der Konvertierung geschrieben wird. |

### Return Value

True, wenn die Konvertierung erfolgreich war, sonst - false.

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint64_t\&) Methode

Konvertiert die angegebene Zeichenkette, die die Zeichenfolgendarstellung einer Zahl enthält, in die entsprechende 64-Bit-Ganzzahl ohne Vorzeichen unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils.

```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint64_t &result)
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Der zu konvertierende String. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Eine bitweise Kombination von Werten des NumberStyles-Enums, die den zulässigen Stil der Zeichenfolgendarstellung einer Zahl angibt. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Zeichenkettenformatinformationen enthält. |
| result | **uint64_t**\& | Die Referenz auf eine 64-Bit-Ganzzahl-Variable ohne Vorzeichen, in die das Ergebnis der Konvertierung geschrieben wird. |

### Return Value

True, wenn die Konvertierung erfolgreich war, sonst - false.

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint64_t\&) Methode

```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint64_t\&) Methode

```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint64_t\&) Methode

```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint64_t &result)
```

## Siehe Auch

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struktur [UInt64](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)
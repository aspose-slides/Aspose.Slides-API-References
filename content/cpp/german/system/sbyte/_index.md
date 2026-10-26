---
title: SByte
second_title: Aspose.Slides für C++ API-Referenz
description: Enthält Methoden, um mit dem 8-bit-Integer zu arbeiten.
type: docs
weight: 1873
url: /de/system/sbyte/
---
## SByte Struktur


Enthält Methoden, um mit dem 8-Bit-Integer zu arbeiten.

```cpp
class SByte
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&) | Konvertiert die angegebene Zeichenkette, die die String-Darstellung einer Zahl enthält, in das entsprechende 8-Bit-vorzeichenbehaftete Ganzzahl. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die String-Darstellung einer Zahl enthält, in das entsprechende 8-Bit-vorzeichenbehaftete Ganzzahl unter Verwendung der bereitgestellten Formatierungsinformationen. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die String-Darstellung einer Zahl enthält, in das entsprechende 8-Bit-vorzeichenbehaftete Ganzzahl unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int8_t**\&) | Konvertiert die angegebene Zeichenkette, die die String-Darstellung einer Zahl enthält, in das entsprechende 8-Bit-vorzeichenbehaftete Ganzzahl. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int8_t**\&) | Konvertiert die angegebene Zeichenkette, die die String-Darstellung einer Zahl enthält, in das entsprechende 8-Bit-vorzeichenbehaftete Ganzzahl unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int8_t**\&) |  |

## Felder

| Feld | Beschreibung |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Größter möglicher Wert. |
| static constexpr [MinValue](./minvalue/) | Kleinster möglicher Wert. |

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)
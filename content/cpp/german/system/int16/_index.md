---
title: Int16
second_title: Aspose.Slides für C++ API Referenz
description: Enthält Methoden zur Arbeit mit dem 16-bit Integer.
type: docs
weight: 1028
url: /de/system/int16/
---
## Int16 Klasse


Contains methods to work with the 16-bit integer.

```cpp
class Int16
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&) | Konvertiert die angegebene Zeichenkette, die die Zeichenkettenrepräsentation einer Zahl enthält, in das entsprechende 16-Bit-Vorzeichen-int. |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die Zeichenkettenrepräsentation einer Zahl enthält, in das entsprechende 16-Bit-Vorzeichen-int unter Verwendung der bereitgestellten Formatierungsinformationen. |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die Zeichenkettenrepräsentation einer Zahl enthält, in das entsprechende 16-Bit-Vorzeichen-int unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils. |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int16_t**\&) | Konvertiert die angegebene Zeichenkette, die die Zeichenkettenrepräsentation einer Zahl enthält, in das entsprechende 16-Bit-Vorzeichen-int. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int16_t**\&) | Konvertiert die angegebene Zeichenkette, die die Zeichenkettenrepräsentation einer Zahl enthält, in das entsprechende 16-Bit-Vorzeichen-int unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int16_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int16_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int16_t**\&) |  |

## Felder

| Feld | Beschreibung |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Größter möglicher Wert. |
| static constexpr [MinValue](./minvalue/) | Kleinster möglicher Wert. |

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)
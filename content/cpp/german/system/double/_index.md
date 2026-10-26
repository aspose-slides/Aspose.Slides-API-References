---
title: Double
second_title: Aspose.Slides für C++ API-Referenz
description: Enthält Methoden zur Arbeit mit dem double-precision Gleitkommawert.
type: docs
weight: 1574
url: /de/system/double/
---
## Double Struktur

Enthält Methoden zur Arbeit mit dem double-precision Gleitkommawert.

```cpp
class Double
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static **double** [Parse](./parse/)(const [String](../string/)\&) | Konvertiert die angegebene Zeichenkette, die die String-Darstellung einer Zahl enthält, in den entsprechenden double-precision Gleitkommawert. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die String-Darstellung einer Zahl enthält, in den entsprechenden double-precision Gleitkommawert unter Verwendung der bereitgestellten Formatierungsinformationen. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die String-Darstellung einer Zahl enthält, in den entsprechenden double-precision Gleitkommawert unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **double**\&) | Konvertiert die angegebene Zeichenkette, die die String-Darstellung einer Zahl enthält, in den entsprechenden double-precision Gleitkommawert. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **double**\&) | Konvertiert die angegebene Zeichenkette, die die String-Darstellung einer Zahl enthält, in den entsprechenden double-precision Gleitkommawert unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **double**\&) |  |

## Felder

| Feld | Beschreibung |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | Kleinster positiver Wert, der größer als Null ist. |
| static constexpr [MaxValue](./maxvalue/) | Größtmöglicher Wert. |
| static constexpr [MinValue](./minvalue/) | Kleinstmöglicher Wert. |
| static constexpr [NaN](./nan/) | Wert, der keine Zahl ist. |
| static constexpr [NegativeInfinity](./negativeinfinity/) | Negative Unendlichkeit. |
| static constexpr [PositiveInfinity](./positiveinfinity/) | Positive Unendlichkeit. |

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)
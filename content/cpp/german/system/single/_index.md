---
title: Single
second_title: Aspose.Slides für C++ API-Referenz
description: Enthält Methoden zur Arbeit mit der Gleitkommazahl einfacher Genauigkeit.
type: docs
weight: 1899
url: /de/system/single/
---
## Einzelner struct

Enthält Methoden zur Arbeit mit der Gleitkommazahl einfacher Genauigkeit.

```cpp
class Single
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static **float** [Parse](./parse/)(const [String](../string/)\&) | Konvertiert die angegebene Zeichenkette, die die Stringdarstellung einer Zahl enthält, in den entsprechenden Gleitkommawert einfacher Genauigkeit. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die Stringdarstellung einer Zahl enthält, in den entsprechenden Gleitkommawert einfacher Genauigkeit unter Verwendung der bereitgestellten Formatierungsinformationen. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die Stringdarstellung einer Zahl enthält, in den entsprechenden Gleitkommawert einfacher Genauigkeit unter Verwendung der bereitgestellten Formatierungsinformationen und Zahlenstil. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **float**\&) | Konvertiert die angegebene Zeichenkette, die die Stringdarstellung einer Zahl enthält, in den entsprechenden Gleitkommawert einfacher Genauigkeit. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **float**\&) | Konvertiert die angegebene Zeichenkette, die die Stringdarstellung einer Zahl enthält, in den entsprechenden Gleitkommawert einfacher Genauigkeit unter Verwendung der bereitgestellten Formatierungsinformationen und Zahlenstil. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **float**\&) |  |

## Felder

| Feld | Beschreibung |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | Kleinster positiver Wert, der größer als Null ist. |
| static constexpr [MaxValue](./maxvalue/) | Größtmöglicher Wert. |
| static constexpr [MinValue](./minvalue/) | Kleinster möglicher Wert. |
| static constexpr [NaN](./nan/) | Wert, der keine Zahl ist. |
| static constexpr [NegativeInfinity](./negativeinfinity/) | Negative Unendlichkeit. |
| static constexpr [PositiveInfinity](./positiveinfinity/) | Positive Unendlichkeit. |

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)
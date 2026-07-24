---
title: UInt64
second_title: Aspose.Slides für C++ API-Referenz
description: Enthält Methoden zur Arbeit mit dem vorzeichenlosen 64-Bit-Integer.
type: docs
weight: 1990
url: /de/system/uint64/
---
## UInt64 struct

Enthält Methoden zur Arbeit mit dem vorzeichenlosen 64-Bit-Integer.

```cpp
class UInt64
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&) | Konvertiert die angegebene Zeichenkette, die die String-Darstellung einer Zahl enthält, in das entsprechende 64-Bit-vorzeichenlose Integer. |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die String-Darstellung einer Zahl enthält, in das entsprechende 64-Bit-vorzeichenlose Integer unter Verwendung der bereitgestellten Formatierungsinformationen. |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die String-Darstellung einer Zahl enthält, in das entsprechende 64-Bit-vorzeichenlose Integer unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenformats. |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint64_t**\&) | Konvertiert die angegebene Zeichenkette, die die String-Darstellung einer Zahl enthält, in das entsprechende 64-Bit-vorzeichenlose Integer. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint64_t**\&) | Konvertiert die angegebene Zeichenkette, die die String-Darstellung einer Zahl enthält, in das entsprechende 64-Bit-vorzeichenlose Integer unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenformats. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint64_t**\&) |  |

## Felder

| Feld | Beschreibung |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Größtmöglicher Wert. |
| static constexpr [MinValue](./minvalue/) | Kleinstmöglicher Wert. |

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)
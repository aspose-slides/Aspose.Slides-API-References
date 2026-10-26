---
title: UInt32
second_title: Aspose.Slides für C++ API Referenz
description: Enthält Methoden zur Arbeit mit dem vorzeichenlosen 32-bit Integer.
type: docs
weight: 1977
url: /de/system/uint32/
---
## UInt32 Struktur

Enthält Methoden zur Arbeit mit dem vorzeichenlosen 32-Bit-Integer.

```cpp
class UInt32
```

## Methoden

| Method | Description |
| --- | --- |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&) | Konvertiert die angegebene Zeichenkette, die die String-Repräsentation einer Zahl enthält, in das äquivalente 32-Bit-Unsigned-Integer. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die String-Repräsentation einer Zahl enthält, in das äquivalente 32-Bit-Unsigned-Integer unter Verwendung der bereitgestellten Formatierungsinformationen. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die String-Repräsentation einer Zahl enthält, in das äquivalente 32-Bit-Unsigned-Integer unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint32_t**\&) | Konvertiert die angegebene Zeichenkette, die die String-Repräsentation einer Zahl enthält, in das äquivalente 32-Bit-Unsigned-Integer. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint32_t**\&) | Konvertiert die angegebene Zeichenkette, die die String-Repräsentation einer Zahl enthält, in das äquivalente 32-Bit-Unsigned-Integer unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint32_t**\&) |  |

## Felder

| Field | Description |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Größter möglicher Wert. |
| static constexpr [MinValue](./minvalue/) | Kleinster möglicher Wert. |

## Siehe auch

* Namespace [System](../)
* Library [Aspose.Slides](../../)
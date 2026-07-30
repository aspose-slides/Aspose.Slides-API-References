---
title: UInt16
second_title: Riferimento API di Aspose.Slides per C++
description: Contiene metodi per lavorare con l'intero senza segno a 16 bit.
type: docs
weight: 1964
url: /it/system/uint16/
---
## UInt16 struct

Contiene metodi per lavorare con l'intero senza segno a 16 bit.

```cpp
class UInt16
```

## Metodi

| Method | Description |
| --- | --- |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel corrispondente intero senza segno a 16 bit. |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel corrispondente intero senza segno a 16 bit usando le informazioni di formattazione fornite. |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel corrispondente intero senza segno a 16 bit usando le informazioni di formattazione e lo stile numerico forniti. |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint16_t**\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel corrispondente intero senza segno a 16 bit. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint16_t**\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel corrispondente intero senza segno a 16 bit usando le informazioni di formattazione e lo stile numerico forniti. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint16_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint16_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint16_t**\&) |  |

## Campi

| Field | Description |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Il valore più grande possibile. |
| static constexpr [MinValue](./minvalue/) | Il valore più piccolo possibile. |

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)
---
title: UInt32
second_title: Riferimento API Aspose.Slides per C++
description: Contiene metodi per lavorare con l'intero senza segno a 32-bit.
type: docs
weight: 1977
url: /it/system/uint32/
---
## UInt32 struct

Contiene metodi per lavorare con l'intero senza segno a 32 bit.

```cpp
class UInt32
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel corrispondente intero senza segno a 32 bit. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel corrispondente intero senza segno a 32 bit utilizzando le informazioni di formattazione fornite. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel corrispondente intero senza segno a 32 bit utilizzando le informazioni di formattazione fornite e lo stile numerico. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint32_t**\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel corrispondente intero senza segno a 32 bit. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint32_t**\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel corrispondente intero senza segno a 32 bit utilizzando le informazioni di formattazione fornite e lo stile numerico. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint32_t**\&) |  |

## Campi

| Campo | Descrizione |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Il valore più grande possibile. |
| static constexpr [MinValue](./minvalue/) | Il valore più piccolo possibile. |

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)
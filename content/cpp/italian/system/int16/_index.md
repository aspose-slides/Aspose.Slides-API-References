---
title: Int16
second_title: Riferimento API di Aspose.Slides per C++
description: Contiene metodi per lavorare con l'intero a 16 bit.
type: docs
weight: 1028
url: /it/system/int16/
---
## Int16 classe

Contiene metodi per lavorare con l'intero a 16 bit.

```cpp
class Int16
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel corrispondente intero con segno a 16 bit. |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel corrispondente intero con segno a 16 bit usando le informazioni di formattazione fornite. |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel corrispondente intero con segno a 16 bit usando le informazioni di formattazione e lo stile numerico forniti. |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int16_t**\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel corrispondente intero con segno a 16 bit. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int16_t**\&) | Converte la stringa specificata contenente la rappresentazione testuale di un numero nel corrispondente intero con segno a 16 bit usando le informazioni di formattazione e lo stile numerico forniti. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int16_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int16_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int16_t**\&) |  |

## Campi

| Campo | Descrizione |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Valore più grande possibile. |
| static constexpr [MinValue](./minvalue/) | Valore più piccolo possibile. |

## Vedi anche

* Namespace [System](../)
* Library [Aspose.Slides](../../)
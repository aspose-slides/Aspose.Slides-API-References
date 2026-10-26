---
title: SByte
second_title: Referencia de API de Aspose.Slides para C++
description: Contiene métodos para trabajar con el entero de 8 bits.
type: docs
weight: 1873
url: /es/system/sbyte/
---
## SByte struct

Contiene métodos para trabajar con el entero de 8 bits.

```cpp
class SByte
```

## Métodos

| Método | Descripción |
| --- | --- |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&) | Convierte la cadena especificada que contiene la representación textual de un número al entero con signo de 8 bits equivalente. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación textual de un número al entero con signo de 8 bits equivalente utilizando la información de formato proporcionada. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación textual de un número al entero con signo de 8 bits equivalente utilizando la información de formato y el estilo numérico proporcionados. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int8_t**\&) | Convierte la cadena especificada que contiene la representación textual de un número al entero con signo de 8 bits equivalente. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int8_t**\&) | Convierte la cadena especificada que contiene la representación textual de un número al entero con signo de 8 bits equivalente utilizando la información de formato y el estilo numérico proporcionados. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int8_t**\&) |  |

## Campos

| Campo | Descripción |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Mayor valor posible. |
| static constexpr [MinValue](./minvalue/) | Menor valor posible. |

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)
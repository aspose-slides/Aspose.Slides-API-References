---
title: Int64
second_title: Referencia de API de Aspose.Slides para C++
description: Contiene métodos para trabajar con el entero de 64 bits.
type: docs
weight: 1054
url: /es/system/int64/
---
## Clase Int64

Contiene métodos para trabajar con el entero de 64 bits.

```cpp
class Int64
```

## Métodos

| Método | Descripción |
| --- | --- |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&) | Convierte la cadena especificada que contiene la representación textual de un número al entero con signo de 64 bits equivalente. |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación textual de un número al entero con signo de 64 bits equivalente utilizando la información de formato proporcionada. |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación textual de un número al entero con signo de 64 bits equivalente utilizando la información de formato y el estilo numérico proporcionados. |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int64_t**\&) | Convierte la cadena especificada que contiene la representación textual de un número al entero con signo de 64 bits equivalente. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int64_t**\&) | Convierte la cadena especificada que contiene la representación textual de un número al entero con signo de 64 bits equivalente utilizando la información de formato y el estilo numérico proporcionados. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int64_t**\&) |  |

## Campos

| Campo | Descripción |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Mayor valor posible. |
| static constexpr [MinValue](./minvalue/) | Menor valor posible. |

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)
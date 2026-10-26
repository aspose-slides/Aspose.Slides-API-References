---
title: UInt64
second_title: Referencia de API de Aspose.Slides para C++
description: Contiene métodos para trabajar con el entero sin signo de 64 bits.
type: docs
weight: 1990
url: /es/system/uint64/
---
## UInt64 struct

Contiene métodos para trabajar con el entero sin signo de 64 bits.

```cpp
class UInt64
```

## Métodos

| Método | Descripción |
| --- | --- |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&) | Convierte la cadena especificada que contiene la representación en forma de cadena de un número al entero sin signo de 64 bits equivalente. |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación en forma de cadena de un número al entero sin signo de 64 bits equivalente usando la información de formato proporcionada. |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación en forma de cadena de un número al entero sin signo de 64 bits equivalente usando la información de formato proporcionada y el estilo numérico. |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint64_t**\&) | Convierte la cadena especificada que contiene la representación en forma de cadena de un número al entero sin signo de 64 bits equivalente. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint64_t**\&) | Convierte la cadena especificada que contiene la representación en forma de cadena de un número al entero sin signo de 64 bits equivalente usando la información de formato proporcionada y el estilo numérico. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint64_t**\&) |  |

## Campos

| Campo | Descripción |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Valor máximo posible. |
| static constexpr [MinValue](./minvalue/) | Valor mínimo posible. |

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)
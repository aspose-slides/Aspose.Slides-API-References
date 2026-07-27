---
title: UInt32
second_title: Referencia de la API de Aspose.Slides para C++
description: Contiene métodos para trabajar con el entero sin signo de 32 bits.
type: docs
weight: 1977
url: /es/system/uint32/
---
## UInt32 struct

Contiene métodos para trabajar con el entero sin signo de 32 bits.

```cpp
class UInt32
```

## Métodos

| Método | Descripción |
| --- | --- |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&) | Convierte la cadena especificada que contiene la representación en forma de cadena de un número al entero sin signo de 32 bits equivalente. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación en forma de cadena de un número al entero sin signo de 32 bits equivalente utilizando la información de formato proporcionada. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación en forma de cadena de un número al entero sin signo de 32 bits equivalente utilizando la información de formato proporcionada y el estilo numérico. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint32_t**\&) | Convierte la cadena especificada que contiene la representación en forma de cadena de un número al entero sin signo de 32 bits equivalente. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint32_t**\&) | Convierte la cadena especificada que contiene la representación en forma de cadena de un número al entero sin signo de 32 bits equivalente utilizando la información de formato proporcionada y el estilo numérico. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint32_t**\&) |  |

## Campos

| Campo | Descripción |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Valor máximo posible. |
| static constexpr [MinValue](./minvalue/) | Valor mínimo posible. |

## Véase también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)
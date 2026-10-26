---
title: Single
second_title: Referencia de la API de Aspose.Slides para C++
description: Contiene métodos para trabajar con el número de punto flotante de precisión simple.
type: docs
weight: 1899
url: /es/system/single/
---
## Struct simple


Contiene métodos para trabajar con el número de punto flotante de precisión simple.

```cpp
class Single
```

## Métodos

| Method | Description |
| --- | --- |
| static **float** [Parse](./parse/)(const [String](../string/)\&) | Convierte la cadena especificada que contiene la representación en forma de cadena de un número al valor de punto flotante de precisión simple equivalente. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación en forma de cadena de un número al valor de punto flotante de precisión simple equivalente utilizando la información de formato proporcionada. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación en forma de cadena de un número al valor de punto flotante de precisión simple equivalente utilizando la información de formato y el estilo numérico proporcionados. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **float**\&) | Convierte la cadena especificada que contiene la representación en forma de cadena de un número al valor de punto flotante de precisión simple equivalente. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **float**\&) | Convierte la cadena especificada que contiene la representación en forma de cadena de un número al valor de punto flotante de precisión simple equivalente utilizando la información de formato y el estilo numérico proporcionados. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **float**\&) |  |

## Campos

| Field | Description |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | Valor positivo más pequeño que es mayor que cero. |
| static constexpr [MaxValue](./maxvalue/) | Valor máximo posible. |
| static constexpr [MinValue](./minvalue/) | Valor mínimo posible. |
| static constexpr [NaN](./nan/) | Valor que no es un número. |
| static constexpr [NegativeInfinity](./negativeinfinity/) | Infinito negativo. |
| static constexpr [PositiveInfinity](./positiveinfinity/) | Infinito positivo. |

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)
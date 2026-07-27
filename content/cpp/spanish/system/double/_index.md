---
title: Double
second_title: Referencia de API de Aspose.Slides para C++
description: Contiene métodos para trabajar con el número de punto flotante de doble precisión.
type: docs
weight: 1574
url: /es/system/double/
---
## Double estructura

Contiene métodos para trabajar con el número de punto flotante de doble precisión.

```cpp
class Double
```

## Métodos

| Método | Descripción |
| --- | --- |
| static **double** [Parse](./parse/)(const [String](../string/)\&) | Convierte la cadena especificada que contiene la representación en cadena de un número al valor equivalente de punto flotante de doble precisión. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación en cadena de un número al valor equivalente de punto flotante de doble precisión utilizando la información de formato proporcionada. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la cadena especificada que contiene la representación en cadena de un número al valor equivalente de punto flotante de doble precisión utilizando la información de formato y el estilo numérico proporcionados. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **double**\&) | Convierte la cadena especificada que contiene la representación en cadena de un número al valor equivalente de punto flotante de doble precisión. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **double**\&) | Convierte la cadena especificada que contiene la representación en cadena de un número al valor equivalente de punto flotante de doble precisión utilizando la información de formato y el estilo numérico proporcionados. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **double**\&) |  |

## Campos

| Campo | Descripción |
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
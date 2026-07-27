---
title: Round()
second_title: Referencia de la API de Aspose.Slides para C++
description: Redondea el valor especificado al número entero más cercano. Un parámetro especifica el comportamiento de la función si el valor especificado está a la misma distancia de los dos números más cercanos.
type: docs
weight: 404
url: /es/system/decimal/round/
---
## Decimal::Round(const Decimal\&, MidpointRounding) método

Redondea el valor especificado al número entero más cercano. Un parámetro especifica el comportamiento de la función si el valor especificado está a la misma distancia de los dos números más cercanos.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, MidpointRounding mode=MidpointRounding::ToEven)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| d | const [Decimal](../)\& | El valor a redondear |
| mode | [MidpointRounding](../../midpointrounding/) | Especifica cómo realizar el redondeo si **value** está a la misma distancia de los dos números más cercanos. |

### Valor devuelto

**d** redondeado al valor entero más cercano

## Decimal::Round(const Decimal\&, int, MidpointRounding) método

Redondea el valor especificado al valor más cercano con el número especificado de dígitos fraccionarios. Un parámetro especifica el comportamiento de la función si el valor especificado está a la misma distancia de los dos números más cercanos.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, int digits, MidpointRounding mode=MidpointRounding::ToEven)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| d | const [Decimal](../)\& | El valor a redondear |
| digits | int | El número de dígitos fraccionarios en el valor redondeado |
| mode | [MidpointRounding](../../midpointrounding/) | Especifica cómo realizar el redondeo si **value** está a la misma distancia de los dos números más cercanos. |

### Valor devuelto

El número con el número especificado de dígitos más cercano a **value**

## Ver también

* Enum [MidpointRounding](../../midpointrounding/)
* Clase [Decimal](../)
* Espacio de nombres [System](../../)
* Library [Aspose.Slides](../../../)
---
title: RoundImpl()
second_title: Referencia de API de Aspose.Slides para C++
description: Redondea el valor especificado al valor más cercano con el número especificado de dígitos fraccionarios. Un parámetro especifica el comportamiento de la función si el valor especificado está igualmente cerca de dos números más cercanos.
type: docs
weight: 287
url: /es/system/mathf/roundimpl/
---
## MathF::RoundImpl(float, int, MidpointRounding) método

Redondea el **value** especificado al valor más cercano con el número especificado de dígitos fraccionarios. Un parámetro especifica el comportamiento de la función si el valor especificado está igualmente cerca de dos números más cercanos.

```cpp
static float System::MathF::RoundImpl(float value, int digits, MidpointRounding mode)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **float** | El value a redondear |
| digits | int | El número de dígitos fraccionarios en el valor redondeado |
| mode | [MidpointRounding](../../midpointrounding/) | Especifica cómo realizar el redondeo si **value** está igualmente cerca de dos números más cercanos. |

### Valor devuelto

El número con el número especificado de dígitos más cercano a **value**

## Ver también

* Enum [MidpointRounding](../../midpointrounding/)
* Struct [MathF](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
---
title: MathF
second_title: Referencia API de Aspose.Slides para C++
description: Contiene funciones matemáticas para valores de punto flotante de precisión simple. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.
type: docs
weight: 1795
url: /es/system/mathf/
---
## MathF struct

Contiene funciones matemáticas para valores de punto flotante de precisión simple. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.

```cpp
class MathF
```

## Métodos

| Método | Descripción |
| --- | --- |
| static T [Abs](./abs/)(T) | Devuelve el valor absoluto del valor especificado. |
| static **float** [Acos](./acos/)(**float**) | Calcula el arcocoseno del valor especificado. |
| static **float** [Asin](./asin/)(**float**) | Calcula el arcoseno del valor especificado. |
| static **float** [Atan](./atan/)(**float**) | Calcula el arcotangente del valor especificado. |
| static **float** [Atan2](./atan2/)(**float**, **float**) | Calcula el arcotangente de la razón de los valores especificados. |
| static **float** [Ceiling](./ceiling/)(**float**) | Devuelve el valor entero más pequeño que sea mayor o igual que el valor especificado. |
| static **float** [Cos](./cos/)(**float**) | Calcula el coseno del valor especificado. |
| static **float** [Cosh](./cosh/)(**float**) | Calcula el coseno hiperbólico del valor especificado. |
| static **float** [Exp](./exp/)(**float**) | Devuelve la constante e elevada a la potencia especificada. |
| static **float** [Floor](./floor/)(**float**) | Devuelve el valor entero más grande que sea menor o igual que el valor especificado. |
| static **float** [IEEERemainder](./ieeeremainder/)(**float**, **float**) | Devuelve el resto resultante de la división de un número especificado por otro número especificado. |
| static **float** [Log](./log/)(**float**) | Devuelve el logaritmo natural del valor especificado. |
| static **float** [Log](./log/)(**float**, **float**) | Devuelve el logaritmo del valor especificado en la base especificada. |
| static **float** [Log10](./log10/)(**float**) | Devuelve el logaritmo base 10 del valor especificado. |
| static **float** [Pow](./pow/)(**float**, **float**) | Devuelve el valor especificado elevado a la potencia especificada. |
| static **float** [Round](./round/)(**float**) | Redondea el valor especificado al entero más cercano. |
| static **float** [Round](./round/)(**float**, int) | Redondea el valor especificado al número más cercano con la cantidad especificada de dígitos fraccionarios. |
| static **float** [Round](./round/)(**float**, [MidpointRounding](../midpointrounding/)) | Redondea el valor especificado al entero más cercano. Un parámetro especifica el comportamiento de la función si el valor especificado está a la misma distancia de dos números más cercanos. |
| static **float** [Round](./round/)(**float**, int, [MidpointRounding](../midpointrounding/)) | Redondea el valor especificado al número más cercano con la cantidad especificada de dígitos fraccionarios. Un parámetro especifica el comportamiento de la función si el valor especificado está a la misma distancia de dos números más cercanos. |
| static **float** [RoundImpl](./roundimpl/)(**float**, int, [MidpointRounding](../midpointrounding/)) | Redondea el valor especificado al número más cercano con la cantidad especificada de dígitos fraccionarios. Un parámetro especifica el comportamiento de la función si el valor especificado está a la misma distancia de dos números más cercanos. |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | Determina el signo del valor entero con signo especificado. |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | Determina el signo del valor de punto flotante especificado. |
| static **float** [Sin](./sin/)(**float**) | Calcula el seno del valor especificado. |
| static **float** [Sinh](./sinh/)(**float**) | Calcula el seno hiperbólico del valor especificado. |
| static **float** [Sqrt](./sqrt/)(**float**) | Devuelve la raíz cuadrada del valor especificado. |
| static **float** [Tan](./tan/)(**float**) | Calcula la tangente del valor especificado. |
| static **float** [Tanh](./tanh/)(**float**) | Calcula la tangente hiperbólica del valor especificado. |
| static **float** [Truncate](./truncate/)(**float**) | Devuelve un valor de punto flotante de precisión simple que tiene la parte entera igual a la del valor especificado, descartando todos los dígitos fraccionarios. |

## Campos

| Campo | Descripción |
| --- | --- |
| static [E](./e/) | Base del logaritmo natural. |
| static constexpr [MaxRoundingDigits](./maxroundingdigits/) |  |
| static [PI](./pi/) | La constante numérica Pi. |
| static [Tau](./tau/) | Valor de Tau. |

## Véase también

* Espacio de nombres [System](../)
* Librería [Aspose.Slides](../../)
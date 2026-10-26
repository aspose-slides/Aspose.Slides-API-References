---
title: Math
second_title: Referencia de API de Aspose.Slides para C++
description: Contiene funciones matemáticas. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.
type: docs
weight: 1782
url: /es/system/math/
---
## Estructura Math

Contiene funciones matemáticas. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.

```cpp
class Math
```

## Métodos

| Método | Descripción |
| --- | --- |
| static T [Abs](./abs/)(T) | Devuelve el valor absoluto del valor especificado. |
| static [Decimal](../decimal/) [Abs](./abs/)(const [Decimal](../decimal/)\&) | Devuelve el valor absoluto de un valor representado por el objeto [Decimal](../decimal/) especificado. |
| static **double** [Acos](./acos/)(**double**) | Calcula el arcocoseno del valor especificado. |
| static **double** [Asin](./asin/)(**double**) | Calcula el arcseno del valor especificado. |
| static **double** [Atan](./atan/)(**double**) | Calcula el arcotangente del valor especificado. |
| static **double** [Atan2](./atan2/)(**double**, **double**) | Calcula la arcotangente de la razón de los valores especificados. |
| static **int64_t** [BigMul](./bigmul/)(int, int) | Devuelve el producto completo de dos enteros de 32 bits. |
| static [Decimal](../decimal/) [Ceiling](./ceiling/)(const [Decimal](../decimal/)\&) | Devuelve el valor entero más pequeño que es mayor o igual que el valor especificado. |
| static **double** [Ceiling](./ceiling/)(**double**) | Devuelve el valor entero más pequeño que es mayor o igual que el valor especificado. |
| static **double** [Cos](./cos/)(**double**) | Calcula el coseno del valor especificado. |
| static **double** [Cosh](./cosh/)(**double**) | Calcula el coseno hiperbólico del valor especificado. |
| static int [DivRem](./divrem/)(int, int, int\&) | Calcula el cociente de dos enteros de 32 bits y el resto. |
| static **int64_t** [DivRem](./divrem/)(**int64_t**, **int64_t**, **int64_t**\&) | Calcula el cociente de dos enteros de 64 bits y el resto. |
| static **double** [Exp](./exp/)(**double**) | Devuelve la constante e elevada a la potencia especificada. |
| static [Decimal](../decimal/) [Floor](./floor/)(const [Decimal](../decimal/)\&) | Devuelve el valor entero más grande que es menor o igual que el valor especificado. |
| static **double** [Floor](./floor/)(**double**) | Devuelve el valor entero más grande que es menor o igual que el valor especificado. |
| static **double** [IEEERemainder](./ieeeremainder/)(**double**, **double**) | Devuelve el resto resultante de la división de un número especificado por otro número especificado. |
| static **double** [Log](./log/)(**double**) | Devuelve el logaritmo natural del valor especificado. |
| static **double** [Log](./log/)(**double**, **double**) | Devuelve el logaritmo del valor especificado en la base especificada. |
| static **double** [Log10](./log10/)(**double**) | Devuelve el logaritmo base 10 del valor especificado. |
| static auto [Max](./max/)(T0, T1) | Devuelve el valor mayor de los dos valores numéricos especificados. |
| static T0 [Max](./max/)(T0, T1) | Devuelve el valor mayor de los dos valores numéricos especificados. |
| **float** [Max_](./max_/)(**float**, **float**) | Devuelve el mayor valor de punto flotante de precisión simple de los dos especificados. |
| **double** [Max_](./max_/)(**double**, **double**) | Devuelve el mayor valor de punto flotante de doble precisión de los dos especificados. |
| static auto [Min](./min/)(T0, T1) | Devuelve el valor menor de los dos valores numéricos especificados. |
| static T0 [Min](./min/)(T0, T1) | Devuelve el valor menor de los dos valores numéricos especificados. |
| **float** [Min_](./min_/)(**float**, **float**) | Devuelve el menor valor de punto flotante de precisión simple de los dos especificados. |
| **double** [Min_](./min_/)(**double**, **double**) | Devuelve el menor valor de punto flotante de doble precisión de los dos especificados. |
| static T [Modulus](./modulus/)(T, T) | Calcula el resto resultante de la división de un valor especificado por otro valor especificado. |
| static **double** [Pow](./pow/)(**double**, **double**) | Devuelve el valor especificado elevado a la potencia especificada. |
| static **double** [Round](./round/)(**double**) | Redondea el valor especificado al entero más cercano. |
| static **double** [Round](./round/)(**double**, int) | Redondea el valor especificado al valor más cercano con el número especificado de dígitos fraccionarios. |
| static **double** [Round](./round/)(**double**, [MidpointRounding](../midpointrounding/)) | Redondea el valor especificado al número entero más cercano. Un parámetro especifica el comportamiento de la función si el valor especificado está a la misma distancia de los dos números más cercanos. |
| static **double** [Round](./round/)(**double**, int, [MidpointRounding](../midpointrounding/)) | Redondea el valor especificado al valor más cercano con el número especificado de dígitos fraccionarios. Un parámetro especifica el comportamiento de la función si el valor especificado está a la misma distancia de los dos números más cercanos. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&) | Redondea el valor especificado al entero más cercano. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int) | Redondea el valor especificado al valor más cercano con el número especificado de dígitos fraccionarios. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, [MidpointRounding](../midpointrounding/)) | Redondea el valor especificado al número entero más cercano. Un parámetro especifica el comportamiento de la función si el valor especificado está a la misma distancia de los dos números más cercanos. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int, [MidpointRounding](../midpointrounding/)) | Redondea el valor especificado al valor más cercano con el número especificado de dígitos fraccionarios. Un parámetro especifica el comportamiento de la función si el valor especificado está a la misma distancia de los dos números más cercanos. |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | Determina el signo del valor entero con signo especificado. |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | Determina el signo del valor de punto flotante especificado. |
| static int [Sign](./sign/)(const [Decimal](../decimal/)\&) | Determina el signo del valor decimal especificado. |
| static **double** [Sin](./sin/)(**double**) | Calcula el seno del valor especificado. |
| static **double** [Sinh](./sinh/)(**double**) | Calcula el seno hiperbólico del valor especificado. |
| static **double** [Sqrt](./sqrt/)(**double**) | Devuelve la raíz cuadrada del valor especificado. |
| static **double** [Tan](./tan/)(**double**) | Calcula la tangente del valor especificado. |
| static **double** [Tanh](./tanh/)(**double**) | Calcula la tangente hiperbólica del valor especificado. |
| static [Decimal](../decimal/) [Truncate](./truncate/)(const [Decimal](../decimal/)\&) | Devuelve el objeto [Decimal](../decimal/) que representa un valor cuya parte entera es igual a la del valor representado por el objeto [Decimal](../decimal/) especificado, con todos los dígitos fraccionarios descartados. |
| static **double** [Truncate](./truncate/)(**double**) | Devuelve un valor de punto flotante de doble precisión cuya parte entera es igual a la del valor especificado, con todos los dígitos fraccionarios descartados. |

## Campos

| Campo | Descripción |
| --- | --- |
| static [E](./e/) | Base del logaritmo natural. |
| static [NaN](./nan/) | Representa un valor no numérico (NaN). |
| static [NegativeInfinity](./negativeinfinity/) | Representa el infinito negativo. |
| static [PI](./pi/) | Constante del número Pi. |
| static [PositiveInfinity](./positiveinfinity/) | Representa el infinito positivo. |

## Observaciones

```cpp
#include "system/math.h"
#include <iostream>

int main()
{
  using namespace System;

  // Imprime los valores absolutos.
  for (int i = -1; i < 2; ++i)
  {
    std::cout << Math::Abs(i) << " ";
  }
  std::cout << std::endl;

  // Imprime el seno de PI/2 y el coseno de PI.
  std::cout << "sin(PI/2)=" << Math::Sin(Math::PI/2) << "; cos(PI)=" << Math::Cos(Math::PI) << std::endl;

  return 0;
}
/*
Este ejemplo de código produce la siguiente salida:
1 0 1
sin(PI/2)=1; cos(PI)=-1
*/
```

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)
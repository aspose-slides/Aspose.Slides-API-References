---
title: Round()
second_title: Referencia de API de Aspose.Slides para C++
description: Redondea el valor especificado al número entero más cercano.
type: docs
weight: 157
url: /es/system/mathf/round/
---
## MathF::Round(float) método


Redondea el valor especificado al número entero más cercano.

```cpp
static float System::MathF::Round(float a)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | **float** | El valor a redondear |

### Valor de retorno

**a** redondeado al número entero más cercano

## MathF::Round(float, int) método


Redondea el valor especificado al número más cercano con la cantidad especificada de dígitos fraccionarios.

```cpp
static float System::MathF::Round(float value, int digits)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **float** | El valor a redondear |
| digits | int | La cantidad de dígitos fraccionarios en el valor redondeado |

### Valor de retorno

El número con la cantidad especificada de dígitos más cercano a **value**

## MathF::Round(float, MidpointRounding) método


Redondea el valor especificado al número entero más cercano. Un parámetro especifica el comportamiento de la función si el valor especificado está a la misma distancia de dos números más cercanos.

```cpp
static float System::MathF::Round(float value, MidpointRounding mode)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **float** | El valor a redondear |
| mode | [MidpointRounding](../../midpointrounding/) | Especifica cómo realizar el redondeo si **value** está a la misma distancia de dos números más cercanos. |

### Valor de retorno

**value** redondeado al número entero más cercano

## MathF::Round(float, int, MidpointRounding) método


Redondea el valor especificado al número más cercano con la cantidad especificada de dígitos fraccionarios. Un parámetro especifica el comportamiento de la función si el valor especificado está a la misma distancia de dos números más cercanos.

```cpp
static float System::MathF::Round(float value, int digits, MidpointRounding mode)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **float** | El valor a redondear |
| digits | int | La cantidad de dígitos fraccionarios en el valor redondeado |
| mode | [MidpointRounding](../../midpointrounding/) | Especifica cómo realizar el redondeo si **value** está a la misma distancia de dos números más cercanos. |

### Valor de retorno

El número con la cantidad especificada de dígitos más cercano a **value**

## Ver también

* Enumeración [MidpointRounding](../../midpointrounding/)
* Estructura [MathF](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)
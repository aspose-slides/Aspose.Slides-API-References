---
title: Round()
second_title: Referencia de la API de Aspose.Slides para C++
description: Redondea el valor especificado al entero más cercano.
type: docs
weight: 157
url: /es/system/math/round/
---
## Math::Round(double) método

Redondea el valor especificado al entero más cercano.

```cpp
static double System::Math::Round(double a)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | **double** | El valor a redondear |

### Valor devuelto

**a** redondeado al entero más cercano

## Math::Round(double, int) método

Redondea el valor especificado al valor más cercano con el número especificado de dígitos fraccionarios.

```cpp
static double System::Math::Round(double value, int digits)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **double** | El valor a redondear |
| digits | int | El número de dígitos fraccionarios en el valor redondeado |

### Valor devuelto

El número con la cantidad especificada de dígitos más cercano a **value**

## Math::Round(double, MidpointRounding) método

Redondea el valor especificado al entero más cercano. Un parámetro especifica el comportamiento de la función si el valor especificado está igualmente cerca de dos números más cercanos.

```cpp
static double System::Math::Round(double value, MidpointRounding mode)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **double** | El valor a redondear |
| mode | [MidpointRounding](../../midpointrounding/) | Especifica cómo realizar el redondeo si **value** está igualmente cerca de dos números más cercanos. |

### Valor devuelto

**value** redondeado al entero más cercano

## Math::Round(double, int, MidpointRounding) método

Redondea el valor especificado al valor más cercano con el número especificado de dígitos fraccionarios. Un parámetro especifica el comportamiento de la función si el valor especificado está igualmente cerca de dos números más cercanos.

```cpp
static double System::Math::Round(double value, int digits, MidpointRounding mode)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **double** | El valor a redondear |
| digits | int | El número de dígitos fraccionarios en el valor redondeado |
| mode | [MidpointRounding](../../midpointrounding/) | Especifica cómo realizar el redondeo si **value** está igualmente cerca de dos números más cercanos. |

### Valor devuelto

El número con la cantidad especificada de dígitos más cercano a **value**

## Math::Round(const Decimal\&) método

Redondea el valor especificado al entero más cercano.

```cpp
static Decimal System::Math::Round(const Decimal &d)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | El valor a redondear |

### Valor devuelto

**d** redondeado al entero más cercano

## Math::Round(const Decimal\&, int) método

Redondea el valor especificado al valor más cercano con el número especificado de dígitos fraccionarios.

```cpp
static Decimal System::Math::Round(const Decimal &value, int digits)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | El valor a redondear |
| digits | int | El número de dígitos fraccionarios en el valor redondeado |

### Valor devuelto

El número con la cantidad especificada de dígitos más cercano a **value**

## Math::Round(const Decimal\&, MidpointRounding) método

Redondea el valor especificado al entero más cercano. Un parámetro especifica el comportamiento de la función si el valor especificado está igualmente cerca de dos números más cercanos.

```cpp
static Decimal System::Math::Round(const Decimal &d, MidpointRounding mode)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | El valor a redondear |
| mode | [MidpointRounding](../../midpointrounding/) | Especifica cómo realizar el redondeo si **value** está igualmente cerca de dos números más cercanos. |

### Valor devuelto

**d** redondeado al entero más cercano

## Math::Round(const Decimal\&, int, MidpointRounding) método

Redondea el valor especificado al valor más cercano con el número especificado de dígitos fraccionarios. Un parámetro especifica el comportamiento de la función si el valor especificado está igualmente cerca de dos números más cercanos.

```cpp
static Decimal System::Math::Round(const Decimal &d, int digits, MidpointRounding mode)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | El valor a redondear |
| digits | int | El número de dígitos fraccionarios en el valor redondeado |
| mode | [MidpointRounding](../../midpointrounding/) | Especifica cómo realizar el redondeo si **value** está igualmente cerca de dos números más cercanos. |

### Valor devuelto

El número con la cantidad especificada de dígitos más cercano a **value**

## Ver también

* Enum [MidpointRounding](../../midpointrounding/)
* Clase [Decimal](../../decimal/)
* Estructura [Math](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)
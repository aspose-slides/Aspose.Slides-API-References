---
title: Enum
second_title: Referencia de API de Aspose.Slides para C++
description: Proporciona métodos que realizan algunas operaciones sobre valores de tipo enum. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.
type: docs
weight: 1587
url: /es/system/enum/
---
## Estructura enum

Proporciona métodos que realizan algunas operaciones sobre valores de tipo enum. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.

```cpp
template<class E,class Guard>class Enum
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| E | El tipo de enum cuyos valores maneja la clase |
| Guard | Tipo de servicio cuyo propósito es garantizar que **E** sea un tipo enumerable |

## Métodos

| Método | Descripción |
| --- | --- |
| static int [Compare](./compare/)(E, T) | Realiza la comparación aritmética de los valores de las constantes de enumeración especificadas. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetDescription](./getdescription/)(T) | Devuelve el nombre de la constante de enumeración que tiene el valor especificado. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetName](./getname/)(T) | Devuelve el nombre de la constante de enumeración que tiene el valor especificado. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() | Devuelve una matriz que contiene los nombres de todos los miembros de la enumeración **E**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() | Devuelve el tipo subyacente de la enumeración. |
| static [ArrayPtr](../arrayptr/)\<E\> [GetValues](./getvalues/)() | Devuelve una matriz que contiene todos los miembros de la enumeración **E**. |
| static **bool** [HasFlag](./hasflag/)(E, E) | Determina si los bits especificados están establecidos en una representación binaria del valor enum especificado. |
| static **bool** [IsDefined](./isdefined/)(E) | Determina si el valor especificado es un miembro del tipo de enumeración **E**. |
| static std::enable_if\<std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, **bool**\>::type [IsDefined](./isdefined/)(T) | Determina si el valor especificado es un miembro del tipo de enumeración **T**. |
| static **bool** [IsDefined](./isdefined/)(const [String](../string/)\&) | Determina si el valor con el nombre especificado se encuentra entre los miembros del enum **E**. |
| static E [Parse](./parse/)(const [String](../string/)\&, **bool**) | Convierte la cadena especificada en la constante de enum equivalente. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, E\&) | Intenta convertir la cadena especificada en la constante de enum equivalente. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**, E\&) | Intenta convertir la cadena especificada en la constante de enum equivalente. |

## Typedefs

| Typedef | Descripción |
| --- | --- |
| [UnderlyingType](./underlyingtype/) | Alias para el tipo subyacente del enum. |

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)
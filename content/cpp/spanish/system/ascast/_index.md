---
title: AsCast()
second_title: Referencia de la API de Aspose.Slides para C++
description: Convierte el tipo de origen al tipo de resultado usando la conversión del operador 'as'. Se usa cuando se necesita una conversión sencilla similar a un constructor.
type: docs
weight: 2640
url: /es/system/ascast/
---
## System::AsCast(const Source\&) función

Convierte el tipo de origen al tipo de resultado usando el operador de conversión 'as'. Se usa cuando se necesita una conversión sencilla similar a un constructor.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::AsCast(const Source &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para convertir. |

### Valor devuelto

El resultado de la conversión.

## System::AsCast(const Source\&) función

Convierte el tipo de origen al tipo de resultado usando el operador de conversión 'as'. Se usa cuando el tipo de origen y el tipo de resultado son los mismos.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::AsCast(const Source &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para convertir. |

### Valor devuelto

El resultado de la conversión.

## System::AsCast(const Source\&) función

Convierte el tipo de origen al tipo de resultado usando el operador de conversión 'as'. Se usa para envoltorios de excepciones.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::AsCast(const Source &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para convertir. |

### Valor devuelto

El resultado de la conversión. Returns nullptr if no conversion available.

## System::AsCast(const Source\&) función

Convierte el tipo de origen al tipo de resultado usando el operador de conversión 'as'. Se usa para convertir un objeto a una excepción.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::AsCast(const Source &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para convertir. |

### Valor devuelto

El resultado de la conversión. Returns nullptr if no conversion available.

## System::AsCast(const Source\&) función

Convierte el tipo de origen al tipo de resultado usando el operador de conversión 'as'. Se usa cuando tanto el origen como el resultado son punteros inteligentes.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para convertir. |

### Valor devuelto

El resultado de la conversión. Returns nullptr if no conversion available.

## System::AsCast(const Source\&) función

Convierte el tipo de origen al tipo de resultado usando el operador de conversión 'as'. Se usa cuando tanto el origen como el resultado son punteros inteligentes (con SmartPtr<...> explícito en el tipo de resultado).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::AsCast(const Source &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para convertir. |

### Valor devuelto

El resultado de la conversión. Returns nullptr if no conversion available.

## System::AsCast(const Source\&) función

Convierte el tipo de origen al tipo de resultado usando el operador de conversión 'as'. Se usa para desempaquetar un objeto a un nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::AsCast(const Source &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para convertir. |

### Valor devuelto

El resultado de la conversión. Returns empty nullable if no conversion available.

## System::AsCast(const Source\&) función

Convierte el tipo de origen al tipo de resultado usando el operador de conversión 'as'. Desempaquetado inválido a un tipo no objeto.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxingToNullable, Result> System::AsCast(const Source &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para convertir. |

### Valor devuelto

Always returns null.

## System::AsCast(const Source\&) función

Desempaquetado inválido a un tipo no objeto.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InvalidUnboxing, Result> System::AsCast(const Source &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para convertir. |

### Valor devuelto

Always returns null.

## System::AsCast(const Source\&) función

Convierte el tipo de origen al tipo de resultado usando el operador de conversión 'as'. Se usa para empaquetar un objeto nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::AsCast(const Source &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para convertir. |

### Valor devuelto

El resultado de la conversión.

## System::AsCast(const Source\&) función

Convierte el tipo de origen al tipo de resultado usando el operador de conversión 'as'. Se usa para empaquetar un objeto común.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para convertir. |

### Valor devuelto

El resultado de la conversión.

## System::AsCast(const Source\&) función

Convierte el tipo de origen al tipo de resultado usando el operador de conversión 'as'. Se usa para empaquetar un objeto común.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para convertir. |

### Valor devuelto

El resultado de la conversión.

## System::AsCast(const Source\&) función

Convierte el tipo de origen al tipo de resultado usando el operador de conversión 'as'. Se usa para desempaquetar una cadena.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToString, Result> System::AsCast(const Source &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para convertir. |

### Valor devuelto

El resultado de la conversión.

## System::AsCast(const Source\&) función

Convierte el tipo de origen al tipo de resultado usando el operador de conversión 'as'. Se usa para castear nullptr.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para convertir. |

### Valor devuelto

El resultado de la conversión.

## System::AsCast(const Source\&) función

Convierte el tipo de origen al tipo de resultado usando el operador de conversión 'as'. Se usa para convertir entre matrices.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) para convertir. |

### Valor devuelto

El resultado de la conversión. Returns nullptr if no conversion for any array member is available.

## Véase también

* Typedef [Exception](../exception/)
* Struct [CastResult](../castresult/)
* Espacio de nombres [System](../)
* Library [Aspose.Slides](../../)
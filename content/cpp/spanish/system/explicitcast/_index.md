---
title: ExplicitCast()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte el tipo de origen al tipo de resultado usando una conversión explícita. Se usa cuando los tipos de origen y de resultado son los mismos.
type: docs
weight: 2627
url: /es/system/explicitcast/
---
## System::ExplicitCast(const Source\&) función


Convierte el tipo de origen al tipo de resultado usando una conversión explícita. Se usa cuando el tipo de origen y el tipo de resultado son los mismos.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::ExplicitCast(const Source &value)
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

The cast result.

## System::ExplicitCast(const Source\&) función


Convierte el tipo de origen al tipo de resultado usando una conversión explícita. Se usa cuando se necesita una conversión simple similar a un constructor.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::ExplicitCast(const Source &value)
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

The cast result.

## System::ExplicitCast(const Source\&) función


Convierte el tipo de origen al tipo de resultado usando una conversión explícita. Se usa para envoltorios de excepciones.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::ExplicitCast(const Source &value)
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

The cast result.

## System::ExplicitCast(const Source\&) función


Convierte el tipo de origen al tipo de resultado usando una conversión explícita. Se usa para convertir un objeto a excepción.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::ExplicitCast(const Source &value)
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

The cast result.

## System::ExplicitCast(const Source\&) función


Convierte el tipo de origen al tipo de resultado usando una conversión explícita. Se usa cuando el origen y el resultado son ambos punteros inteligentes (sin SmartPtr<...> explícito en el tipo de resultado).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
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

The cast result.

## System::ExplicitCast(Source) función


Convierte el tipo de origen al tipo de resultado usando una conversión explícita. Se usa al convertir un puntero crudo a puntero inteligente.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::RawPointer, typename CastResult<std::remove_pointer_t<Result>>::type> System::ExplicitCast(Source value)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | Source | [Object](../object/) para convertir. |

### Valor devuelto

The cast result.

## System::ExplicitCast(const Source\&) función


Convierte el tipo de origen al tipo de resultado usando una conversión explícita. Se usa cuando el origen y el resultado son ambos punteros inteligentes (con SmartPtr<...> explícito en el tipo de resultado).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::ExplicitCast(const Source &value)
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

The cast result.

## System::ExplicitCast(const Source\&) función


Convierte el tipo de origen al tipo de resultado usando una conversión explícita. Se usa para desempaquetar objeto a nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::ExplicitCast(const Source &value)
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

The cast result.

## System::ExplicitCast(const Source\&) función


Convierte el tipo de origen al tipo de resultado usando una conversión explícita. Se usa para empaquetar nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::ExplicitCast(const Source &value)
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

The cast result.

## System::ExplicitCast(const Source\&) función


Convierte el tipo de origen al tipo de resultado usando una conversión explícita. Se usa para desempaquetar objeto nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableUnboxing, Result> System::ExplicitCast(const Source &value)
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

The cast result.

## System::ExplicitCast(const Source\&) función


Convierte el tipo de origen al tipo de resultado usando una conversión explícita. Se usa para empaquetar enumeraciones.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::EnumBoxing, SmartPtr<BoxedValueBase>> System::ExplicitCast(const Source &value)
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

The cast result.

## System::ExplicitCast(const Source\&) función


Convierte el tipo de origen al tipo de resultado usando una conversión explícita. Se usa para copiar tipos de valor al heap cuando el tipo de valor debe referenciarse como puntero inteligente (en genéricos restringidos con un tipo de interfaz pero especializados con una estructura que implementa dicha interfaz).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::HeapifyBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
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

The cast result.

## System::ExplicitCast(const Source\&) función


Convierte el tipo de origen al tipo de resultado usando una conversión explícita. Se usa para obtener interfaces a partir de tipos de valor.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
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

The cast result.

## System::ExplicitCast(const Source\&) función


Convierte el tipo de origen al tipo de resultado usando una conversión explícita. Se usa para empaquetado común.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
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

The cast result.

## System::ExplicitCast(const Source\&) función


Convierte el tipo de origen al tipo de resultado usando una conversión explícita. Se usa para empaquetado [System::String](../string/).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::StringBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
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

The cast result.

## System::ExplicitCast(const Source\&) función


Convierte el tipo de origen al tipo de resultado usando una conversión explícita. Se usa para desempaquetar interfaces.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxing, Result> System::ExplicitCast(const Source &value)
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

The cast result.

## System::ExplicitCast(const Source\&) función


Convierte el tipo de origen al tipo de resultado usando una conversión explícita. Se usa para desempaquetado común.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Unboxing, Result> System::ExplicitCast(const Source &value)
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

The cast result.

## System::ExplicitCast(const Source\&) función


Convierte el tipo de origen al tipo de resultado usando una conversión explícita. Se usa para convertir nullptr.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
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

The cast result.

## System::ExplicitCast(const Source\&) función


Convierte el tipo de origen al tipo de resultado usando una conversión explícita. Se usa para convertir entre matrices.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
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

The cast result.

## Véase también

* Typedef [Exception](../exception/)
* Class [SmartPtr](../smartptr/)
* Class [BoxedValueBase](../boxedvaluebase/)
* Struct [CastResult](../castresult/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)
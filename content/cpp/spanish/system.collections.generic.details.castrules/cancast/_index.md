---
title: CanCast()
second_title: Referencia de la API de Aspose.Slides para C++
description: Comprueba la posibilidad de conversión.
type: docs
weight: 40
url: /es/system.collections.generic.details.castrules/cancast/
---
## System::Collections::Generic::Details::CastRules::CanCast(Source) función


Comprueba la posibilidad de conversión.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Source | El tipo de origen. |
| Result | El tipo de resultado. |

### Valor devuelto

True cuando un valor distinto de nullptr se devuelve después de la conversión, de lo contrario false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) función


Comprueba la posibilidad de conversión.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Source | El tipo de origen. |
| Result | El tipo de resultado. |

### Valor devuelto

True cuando un valor distinto de nullptr se devuelve después de la conversión, de lo contrario false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) función


Comprueba la posibilidad de conversión.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Source | El tipo de origen. |
| Result | El tipo de resultado. |

### Valor devuelto

True cuando un valor distinto de nullptr se devuelve después de la conversión, de lo contrario false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) función


Comprueba la posibilidad de conversión.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Source | El tipo de origen. |
| Result | El tipo de resultado. |

### Valor devuelto

Siempre devuelve true.

## System::Collections::Generic::Details::CastRules::CanCast(Source) función


Comprueba la posibilidad de conversión.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Source | El tipo de origen. |
| Result | El tipo de resultado. |

### Valor devuelto

True cuando un valor distinto de nullptr se devuelve después de la conversión, de lo contrario false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) función


Comprueba la posibilidad de conversión.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Source | El tipo de origen. |
| Result | El tipo de resultado. |

### Valor devuelto

Siempre devuelve true.

## System::Collections::Generic::Details::CastRules::CanCast(Source) función


Comprueba la posibilidad de conversión.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Source | El tipo de origen. |
| Result | El tipo de resultado. |

### Valor devuelto

True si la operación de conversión se realizó con éxito, de lo contrario false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) función


Comprueba la posibilidad de conversión.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Source | El tipo de origen. |
| Result | El tipo de resultado. |

### Valor devuelto

Siempre devuelve false.

## Ver también

* Estructura [CastType](../casttype/)
* Espacio de nombres [System::Collections::Generic::Details::CastRules](../)
* Biblioteca [Aspose.Slides](../../)
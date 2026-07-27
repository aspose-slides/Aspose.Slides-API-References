---
title: Cast()
second_title: Referencia de la API de Aspose.Slides para C++
description: Convierte el tipo de origen al tipo de resultado. Se usa cuando el tipo de origen y el tipo de resultado son los mismos.
type: docs
weight: 14
url: /es/system.collections.generic.details.castrules/cast/
---
## System::Collections::Generic::Details::CastRules::Cast(Source) función

Convierte el tipo de origen al tipo de resultado. Se usa cuando el tipo de origen y el tipo de resultado son los mismos.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Source | El tipo de origen. |
| Result | El tipo de resultado. |

### Valor devuelto

El resultado del casting.

## System::Collections::Generic::Details::CastRules::Cast(Source) función

Convierte el tipo de origen al tipo de resultado. Se usa cuando el tipo de origen puede convertirse estáticamente al tipo de resultado.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Source | El tipo de origen. |
| Result | El tipo de resultado. |

### Valor devuelto

El resultado del casting.

## System::Collections::Generic::Details::CastRules::Cast(Source) función

Convierte el tipo de origen al tipo de resultado. Se usa cuando los tipos no son los mismos y el tipo de origen no puede convertirse estáticamente al tipo de resultado.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Source | El tipo de origen. |
| Result | El tipo de resultado. |

### Valor devuelto

El resultado del casting.

## System::Collections::Generic::Details::CastRules::Cast(Source) función

Convierte el tipo de origen al tipo de resultado. Se usa cuando el tipo de origen se está encapsulando en la instancia de la clase [Nullable](../../system/nullable/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Source | El tipo de origen. |
| Result | El tipo de resultado. |

### Valor devuelto

El resultado del casting.

## System::Collections::Generic::Details::CastRules::Cast(Source) función

Convierte el tipo de origen al tipo de resultado. Se usa cuando el tipo de origen se está desencapsulando de la instancia de la clase [Nullable](../../system/nullable/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Source | El tipo de origen. |
| Result | El tipo de resultado. |

### Valor devuelto

El resultado del casting.

## System::Collections::Generic::Details::CastRules::Cast(Source) función

Convierte el tipo de origen al tipo de resultado. Se usa cuando el tipo de origen se está encapsulando en la instancia de la clase [Object](../../system/object/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Source | El tipo de origen. |
| Result | El tipo de resultado. |

### Valor devuelto

El resultado del casting.

## System::Collections::Generic::Details::CastRules::Cast(Source) función

Convierte el tipo de origen al tipo de resultado. Se usa cuando el tipo de origen se está desencapsulando de la instancia de la clase [Object](../../system/object/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Source | El tipo de origen. |
| Result | El tipo de resultado. |

### Valor devuelto

El resultado del casting.

## System::Collections::Generic::Details::CastRules::Cast(Source) función

Convierte el tipo de origen al tipo de resultado. Se usa cuando la conversión no es válida o la conversión es explícita.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, Result> System::Collections::Generic::Details::CastRules::Cast(Source)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Source | El tipo de origen. |
| Result | El tipo de resultado. |

### Valor devuelto

El resultado del casting.

## Ver también

* Estructura [CastType](../casttype/)
* Espacio de nombres [System::Collections::Generic::Details::CastRules](../)
* Biblioteca [Aspose.Slides](../../)
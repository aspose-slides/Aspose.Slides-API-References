---
title: StaticCast()
second_title: Referencia de API de Aspose.Slides para C++
description: Realiza una conversión estática en objetos SmartPtr.
type: docs
weight: 2562
url: /es/system/staticcast/
---
## System::StaticCast(SmartPtr\<TFrom\> const\&) función


Realiza una conversión estática en [SmartPtr](../smartptr/) objetos.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast(SmartPtr<TFrom> const &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TTo | Tipo apuntado objetivo. |
| TFrom | Tipo apuntado de origen. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Puntero de origen. |

### Valor devuelto

Resultado de la conversión si la conversión está permitida.

Obsoleto
:   Mantener por compatibilidad retroactiva. Utilice ExplicitCast en su lugar.

## System::StaticCast(WeakPtr\<TFrom\> const\&) función


Realiza una conversión estática en [WeakPtr](../weakptr/) objetos.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast(WeakPtr<TFrom> const &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TTo | Tipo apuntado objetivo. |
| TFrom | Tipo apuntado de origen. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | Puntero de origen. |

### Valor devuelto

Resultado de la conversión si la conversión está permitida.

Obsoleto
:   Mantener por compatibilidad retroactiva. Utilice ExplicitCast en su lugar.

## System::StaticCast(std::nullptr_t) función


Realiza una conversión estática de objetos nulos.

```cpp
template<typename TTo> CastResult<TTo>::type System::StaticCast(std::nullptr_t)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TTo | Tipo apuntado objetivo. |

### Valor devuelto

nullptr.

Obsoleto
:   Mantener por compatibilidad retroactiva. Utilice ExplicitCast en su lugar.

## System::StaticCast(TFrom) función


Especialización para tipos aritméticos.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(TFrom value)
```

## System::StaticCast(TTo) función


Procesa la conversión de [String](../string/) a [String](../string/).

```cpp
template<typename TTo> std::enable_if<std::is_same<TTo, System::String>::value, TTo>::type System::StaticCast(TTo value)
```

## System::StaticCast(const TFrom *) función


Especialización para tipos aritméticos.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom *value)
```

## System::StaticCast(const TFrom\&) función


Realiza una conversión estática en objetos que no son punteros.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_same<TFrom, System::String>::value &&!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&!std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TTo | Tipo objetivo. |
| TFrom | Tipo de origen. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const TFrom\& | Objeto de origen. |

### Valor devuelto

Resultado de la conversión si la conversión está permitida.

Obsoleto
:   Mantener por compatibilidad retroactiva. Utilice ExplicitCast en su lugar.

## System::StaticCast(const TFrom\&) función


Realiza una conversión estática en objetos Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast(const TFrom &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TTo | Tipo Exception objetivo. |
| TFrom | Tipo Exception de origen. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const TFrom\& | Puntero de origen. |

### Valor devuelto

Resultado de la conversión si la conversión está permitida.

Obsoleto
:   Mantener por compatibilidad retroactiva. Utilice ExplicitCast en su lugar.

## System::StaticCast(SmartPtr\<TFrom\>) función


Realiza una conversión estática en Objetos a objetos Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast(SmartPtr<TFrom> obj) noexcept
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TTo | Tipo Exception objetivo. |
| TFrom | [Object](../object/) tipo. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Puntero de origen. |

### Valor devuelto

Resultado de la conversión si la conversión está permitida.

Obsoleto
:   Mantener por compatibilidad retroactiva. Utilice ExplicitCast en su lugar.

## Ver también

* Clase [SmartPtr](../smartptr/)
* Clase [WeakPtr](../weakptr/)
* Clase [String](../string/)
* Clase [Object](../object/)
* Estructura [IsExceptionWrapper](../isexceptionwrapper/)
* Estructura [CastResult](../castresult/)
* Estructura [IsSmartPtr](../issmartptr/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)
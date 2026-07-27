---
title: DynamicCast()
second_title: Referencia de API de Aspose.Slides para C++
description: Realiza un casting dinámico en objetos Exception.
type: docs
weight: 2536
url: /es/system/dynamiccast/
---
## System::DynamicCast(const TFrom\&) función


Realiza un casting dinámico en objetos Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast(const TFrom &obj)
```


### Parámetros de plantilla

| Parameter | Description |
| --- | --- |
| TTo | Tipo Exception de destino. |
| TFrom | Tipo Exception de origen. |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | Puntero de origen. |

### Valor devuelto

Resultado del cast si el cast está permitido.

Obsoleto
:   Mantener por compatibilidad hacia atrás. Use ExplicitCast en su lugar.

## System::DynamicCast(SmartPtr\<TFrom\> const\&) función


Realiza un casting dinámico en objetos [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_enum<TTo>::value &&!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast(SmartPtr<TFrom> const &obj)
```


### Parámetros de plantilla

| Parameter | Description |
| --- | --- |
| TTo | Tipo del punteado de destino. |
| TFrom | Tipo del punteado de origen. |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Puntero de origen. |

### Valor devuelto

Resultado del cast si el cast está permitido.

Obsoleto
:   Mantener por compatibilidad hacia atrás. Use ExplicitCast en su lugar.

## System::DynamicCast(SmartPtr\<TFrom\>) función


Desempaqueta un enum empaquetado mediante cast.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_enum<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```


### Parámetros de plantilla

| Parameter | Description |
| --- | --- |
| TTo | Tipo enum de destino. |
| TFrom | Tipo del punteado de origen. |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Puntero al objeto del que desempaquetar datos. |

### Valor devuelto

Valor del enum desempaquetado.

Obsoleto
:   Mantener por compatibilidad hacia atrás. Use ExplicitCast en su lugar.

## System::DynamicCast(std::nullptr_t) función


Realiza un casting dinámico de objetos nulos.

```cpp
template<typename TTo> CastResult<TTo>::type System::DynamicCast(std::nullptr_t) noexcept
```


### Parámetros de plantilla

| Parameter | Description |
| --- | --- |
| TTo | Tipo del punteado de destino. |

### Valor devuelto

nullptr.

Obsoleto
:   Mantener por compatibilidad hacia atrás. Use ExplicitCast en su lugar.

## System::DynamicCast(TFrom\&) función


Realiza un casting dinámico en objetos que no son punteros.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&std::is_convertible<TTo, TFrom>::value, TTo>::type System::DynamicCast(TFrom &obj)
```


### Parámetros de plantilla

| Parameter | Description |
| --- | --- |
| TTo | Tipo de destino. |
| TFrom | Tipo de origen. |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| obj | TFrom\& | Objeto de origen. |

### Valor devuelto

Resultado del cast.

Obsoleto
:   Mantener por compatibilidad hacia atrás. Use ExplicitCast en su lugar.

## System::DynamicCast(SmartPtr\<TFrom\>) función


Realiza un casting dinámico en Objects a objetos Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```


### Parámetros de plantilla

| Parameter | Description |
| --- | --- |
| TTo | Tipo Exception de destino. |
| TFrom | Tipo [Object](../object/). |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Puntero de origen. |

### Valor devuelto

Resultado del cast si el cast está permitido.

Obsoleto
:   Mantener por compatibilidad hacia atrás. Use ExplicitCast en su lugar.

## System::DynamicCast(TFrom) función


Realiza un casting dinámico de IntPtr a puntero.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_pointer<TTo>::value &&std::is_same<IntPtr, TFrom>::value, TTo>::type System::DynamicCast(TFrom value) noexcept
```


### Parámetros de plantilla

| Parameter | Description |
| --- | --- |
| TTo | Tipo de destino. |
| TFrom | Tipo de origen. |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| value | TFrom | Valor IntPtr de origen. |

### Valor devuelto

Resultado del cast.

Obsoleto
:   Mantener por compatibilidad hacia atrás. Use ExplicitCast en su lugar.

## Ver también

* Clase [SmartPtr](../smartptr/)
* Clase [Object](../object/)
* Estructura [IsExceptionWrapper](../isexceptionwrapper/)
* Estructura [CastResult](../castresult/)
* Estructura [IsSmartPtr](../issmartptr/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)
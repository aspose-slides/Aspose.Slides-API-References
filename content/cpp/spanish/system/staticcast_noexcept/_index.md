---
title: StaticCast_noexcept()
second_title: Referencia de la API de Aspose.Slides para C++
description: Realiza una conversión estática en objetos SmartPtr.
type: docs
weight: 2549
url: /es/system/staticcast_noexcept/
---
## System::StaticCast_noexcept(SmartPtr\<TFrom\> const\&) función


Realiza una conversión estática en objetos [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast_noexcept(SmartPtr<TFrom> const &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TTo | Tipo apuntado de destino. |
| TFrom | Tipo apuntado de origen. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Puntero de origen. |

### Valor de retorno

Resultado de la conversión si se permite la conversión o nullptr en caso contrario.

Obsoleto
:   Se mantiene por compatibilidad hacia atrás. Use AsCast en su lugar.

## System::StaticCast_noexcept(WeakPtr\<TFrom\> const\&) función


Realiza una conversión estática en objetos [WeakPtr](../weakptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast_noexcept(WeakPtr<TFrom> const &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TTo | Tipo apuntado de destino. |
| TFrom | Tipo apuntado de origen. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | Puntero de origen. |

### Valor de retorno

Resultado de la conversión si se permite la conversión o nullptr en caso contrario.

Obsoleto
:   Se mantiene por compatibilidad hacia atrás. Use AsCast en su lugar.

## System::StaticCast_noexcept(const TFrom\&) función


Realiza una conversión estática en objetos Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast_noexcept(const TFrom &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TTo | Tipo de excepción de destino. |
| TFrom | Tipo de excepción de origen. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const TFrom\& | Puntero de origen. |

### Valor de retorno

Resultado de la conversión si se permite la conversión o nullptr en caso contrario.

Obsoleto
:   Se mantiene por compatibilidad hacia atrás. Use AsCast en su lugar.

## System::StaticCast_noexcept(SmartPtr\<TFrom\>) función


Realiza una conversión estática en Objects a objetos Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast_noexcept(SmartPtr<TFrom> obj) noexcept
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TTo | Tipo de excepción de destino. |
| TFrom | Tipo [Object](../object/). |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Puntero de origen. |

### Valor de retorno

Resultado de la conversión si se permite la conversión o nullptr en caso contrario.

Obsoleto
:   Se mantiene por compatibilidad hacia atrás. Use AsCast en su lugar.

## Ver también

* Clase [SmartPtr](../smartptr/)
* Clase [WeakPtr](../weakptr/)
* Clase [Object](../object/)
* Estructura [IsExceptionWrapper](../isexceptionwrapper/)
* Estructura [CastResult](../castresult/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)
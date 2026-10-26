---
title: DynamicCast_noexcept()
second_title: Referencia de API de Aspose.Slides para C++
description: Conversiones antiguas obsoletas. Se eliminarán en versiones futuras.
type: docs
weight: 2523
url: /es/system/dynamiccast_noexcept/
---
## System::DynamicCast_noexcept(const TFrom\&) function

Conversiones obsoletas antiguas. Se eliminarán en versiones futuras.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast_noexcept(const TFrom &obj) noexcept
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

Resultado de la conversión si la conversión está permitida o nullptr en caso contrario.

## Observaciones

Realiza una conversión dinámica en objetos Exception. Obsoleto
:   Se mantiene por compatibilidad retroactiva. Use AsCast en su lugar.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\> const\&) function

Realiza una conversión dinámica en objetos [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast_noexcept(SmartPtr<TFrom> const &obj) noexcept
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TTo | Tipo de puntero de destino. |
| TFrom | Tipo de puntero de origen. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Puntero de origen. |

### Valor de retorno

Resultado de la conversión si la conversión está permitida o nullptr en caso contrario.

Obsoleto
:   Se mantiene por compatibilidad retroactiva. Use AsCast en su lugar.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\>) function

Realiza una conversión dinámica en objetos a objetos Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast_noexcept(SmartPtr<TFrom> obj) noexcept
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TTo | Tipo de excepción de destino. |
| TFrom | tipo [Object](../object/). |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Puntero de origen. |

### Valor de retorno

Resultado de la conversión si la conversión está permitida o nullptr en caso contrario.

Obsoleto
:   Se mantiene por compatibilidad retroactiva. Use AsCast en su lugar.

## Véase también

* Clase [SmartPtr](../smartptr/)
* Clase [Object](../object/)
* Estructura [IsExceptionWrapper](../isexceptionwrapper/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)
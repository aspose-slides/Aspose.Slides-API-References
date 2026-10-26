---
title: Cast_noexcept()
second_title: Referencia de API de Aspose.Slides para C++
description: Realiza una conversión en objetos SmartPtr.
type: docs
weight: 2497
url: /es/system/cast_noexcept/
---
## System::Cast_noexcept(SmartPtr\<TFrom\> const\&) función


Realiza conversión en objetos [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast_noexcept(SmartPtr<TFrom> const &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TTo | Tipo del puntero objetivo. |
| TFrom | Tipo del puntero origen. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Puntero origen. |

### Valor devuelto

Resultado de la conversión si la conversión está permitida o nullptr en caso contrario.

## Ver también

* Clase [SmartPtr](../smartptr/)
* Estructura [IsExceptionWrapper](../isexceptionwrapper/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)
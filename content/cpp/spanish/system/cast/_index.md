---
title: Cast()
second_title: Referencia de API de Aspose.Slides para C++
description: Realiza un casting en objetos SmartPtr.
type: docs
weight: 2510
url: /es/system/cast/
---
## System::Cast(SmartPtr\<TFrom\> const\&) función

Realiza un casting en objetos [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast(SmartPtr<TFrom> const &obj)
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

## Valor devuelto

Resultado del cast si el cast está permitido.

## Ver también

* Clase [SmartPtr](../smartptr/)
* Estructura [IsExceptionWrapper](../isexceptionwrapper/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)
---
title: ForceStaticCast()
second_title: Referencia de API de Aspose.Slides para C++
description: Realiza un casting estático real en objetos SmartPtr.
type: docs
weight: 2588
url: /es/system/forcestaticcast/
---
## System::ForceStaticCast(SmartPtr\<TFrom\> const\&) función

Realiza un casting estático real en objetos [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ForceStaticCast(SmartPtr<TFrom> const &obj)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TTo | Tipo del puntero al que apunta. |
| TFrom | Tipo de puntero origen. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Puntero fuente. |

### Valor de retorno

Resultado del cast si el cast está permitido; de lo contrario, el comportamiento es indefinido.

## Ver también

* Clase [SmartPtr](../smartptr/)
* Estructura [CastResult](../castresult/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)
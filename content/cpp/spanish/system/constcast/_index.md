---
title: ConstCast()
second_title: Referencia de API de Aspose.Slides para C++
description: Fin de conversiones obsoletas.
type: docs
weight: 2575
url: /es/system/constcast/
---
## System::ConstCast(const SmartPtr\<TFrom\>\&) función


Fin de conversiones obsoletas.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ConstCast(const SmartPtr<TFrom> &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TTo | Tipo del punteado de destino. |
| TFrom | Tipo del punteado de origen. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [SmartPtr](../smartptr/)\<TFrom\>\& | Puntero de origen. |

### Valor devuelto

Resultado del cast si el cast está permitido o nullptr en caso contrario.
## Observaciones


Realiza un const cast sobre objetos [SmartPtr](../smartptr/). 
## Véase también

* Clase [SmartPtr](../smartptr/)
* Estructura [CastResult](../castresult/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)
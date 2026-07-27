---
title: ArrayInitializerCast()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte valores fundamentales de arrays (que C# hace implícitamente pero C++ aparentemente no lo hace).
type: docs
weight: 209
url: /es/system/objectext/arrayinitializercast/
---
## ObjectExt::ArrayInitializerCast(From ...) método


Convierte valores fundamentales de arrays (que C# hace implícitamente pero C++ aparentemente no lo hace).

```cpp
template<typename To,typename ...> static std::enable_if<(std::is_fundamental<To>::value), std::array<To, sizeof...(From)>>::type System::ObjectExt::ArrayInitializerCast(From ...args)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| To | Tipo de destino. |
| From | Tipos de origen. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| args | From ... | Valores a convertir y agregar al array de destino. |

### Valor devuelto

[Array](../../array/) que contiene copias convertidas de todos los argumentos en el mismo orden.

## Ver también

* Clase [ObjectExt](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)
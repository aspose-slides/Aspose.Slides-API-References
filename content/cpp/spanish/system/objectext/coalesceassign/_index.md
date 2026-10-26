---
title: CoalesceAssign()
second_title: Referencia de la API de Aspose.Slides para C++
description: Implementación de la traducción del operador '??='.
type: docs
weight: 183
url: /es/system/objectext/coalesceassign/
---
## ObjectExt::CoalesceAssign(T0\&, T1) método


Implementación de la traducción del operador '??='.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::CoalesceAssign(T0 &value, T1 func) -> T0 &
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T0 | LHS value type. |
| T1 | Type of lambda encapsulating RHS expression. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | T0\& | LHS value. |
| func | T1 | RHS expression. |

### Valor devuelto

Si el valor LHS no es nulo, devuelve LHS; de lo contrario calcula la expresión RHS y devuelve el resultado.

## Ver también

* Clase [ObjectExt](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)
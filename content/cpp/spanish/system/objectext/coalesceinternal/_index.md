---
title: CoalesceInternal()
second_title: Referencia de API de Aspose.Slides para C++
description: Implementación de la traducción del operador '??' para tipos no anulables. Sobrecarga para el caso en que RT2 sea convertible a RT1.
type: docs
weight: 157
url: /es/system/objectext/coalesceinternal/
---
## ObjectExt::CoalesceInternal(RT1, F) método

Implementación de la traducción del operador '??' para tipos no anulables. Sobrecarga para el caso en que RT2 sea convertible a RT1.

```cpp
template<typename RT1,typename RT2,typename F> static std::conditional<std::is_convertible<RT2, RT1>::value, RT1, RT2>::type System::ObjectExt::CoalesceInternal(RT1 value, F func)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T0 | tipo de valor LHS. |
| T1 | Tipo de lambda que encapsula la expresión RHS. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | RT1 | valor LHS. |
| func | F | expresión RHS. |

### Valor de retorno

Si el valor LHS no es nulo, devuelve LHS; de lo contrario, calcula la expresión RHS y devuelve el resultado.

## Ver también

* Clase [ObjectExt](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)
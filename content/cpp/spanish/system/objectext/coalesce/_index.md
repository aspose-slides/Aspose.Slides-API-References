---
title: Coalesce()
second_title: Referencia de API de Aspose.Slides para C++
description: Implementación de la traducción del operador '??' para tipos no anulables.
type: docs
weight: 170
url: /es/system/objectext/coalesce/
---
## ObjectExt::Coalesce(T0, T1) método

Implementación de la traducción del operador '??' para tipos no anulables.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::Coalesce(T0 value, T1 func)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T0 | Valor LHS. |
| T1 | Tipo de lambda que encapsula la expresión RHS. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | T0 | Valor LHS. |
| func | T1 | Expresión RHS. |

### Valor devuelto

Si el valor LHS no es nulo, devuelve LHS; de lo contrario, calcula la expresión RHS y devuelve el resultado.

## ObjectExt::Coalesce(System::Nullable\<T0\>, T1) método

Implementación de la traducción del operador '??' para tipos anulables.

```cpp
template<typename T0,typename T1> static T0 System::ObjectExt::Coalesce(System::Nullable<T0> value, T1 func)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T0 | Valor LHS. |
| T1 | Tipo de lambda que encapsula la expresión RHS. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [System::Nullable](../../nullable/)\<T0\> | Valor LHS. |
| func | T1 | Expresión RHS. |

### Valor devuelto

Si el valor LHS no es nulo, devuelve LHS; de lo contrario, calcula la expresión RHS y devuelve el resultado.

## Ver también

* Clase [ObjectExt](../)
* Clase [Nullable](../../nullable/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)
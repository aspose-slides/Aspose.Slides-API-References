---
title: Equals()
second_title: Referencia de API de Aspose.Slides para C++
description: Determina si el valor representado por el objeto actual es igual al valor representado por el objeto Nullable especificado.
type: docs
weight: 131
url: /es/system/nullable/equals/
---
## Nullable::Equals(const T1\&) const método

Determina si el valor representado por el objeto actual es igual al valor representado por el objeto [Nullable](../) especificado.

```cpp
template<typename T1> std::enable_if<IsNullable<T1>::value, bool>::type System::Nullable<T>::Equals(const T1 &other) const
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | El tipo subyacente del objeto [Nullable](../) con el que comparar |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | const T1\& | Una referencia constante al objeto [Nullable](../) con el que comparar |

### Valor de retorno

True si el valor representado por el objeto actual es igual al valor representado por el objeto [Nullable](../) especificado, de lo contrario - false

## Ver también

* Clase [Nullable](../)
* Estructura [IsNullable](../../isnullable/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)
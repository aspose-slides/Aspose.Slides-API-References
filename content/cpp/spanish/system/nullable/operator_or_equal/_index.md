---
title: operator|=()
second_title: Aspose.Slides para C++ Referencia de API
description: Aplica operator|=() al valor representado por el objeto actual usando el valor especificado como argumento del lado derecho.
type: docs
weight: 261
url: /es/system/nullable/operator_or_equal/
---
## Nullable::operator|=(bool) método


Aplica [operator|=()](./) al valor representado por el objeto actual usando el valor especificado como argumento del lado derecho.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator|=(bool other)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | El parámetro de plantilla para hacer que SFINAE funcione. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | **bool** | Un valor booleano que se usa como valor del lado derecho del [operator|=()](./) aplicado al valor representado por el objeto actual. |

### Valor de retorno

Una referencia al propio objeto.

## Ver también

* Clase [Nullable](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)
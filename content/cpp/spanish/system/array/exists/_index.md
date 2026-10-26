---
title: Exists()
second_title: Referencia de API de Aspose.Slides para C++
description: Determina si el objeto Array especificado contiene un elemento que satisface los requisitos del predicado especificado.
type: docs
weight: 781
url: /es/system/array/exists/
---
## Array::Exists(ArrayPtr\<T\>, std::function\<bool(T)>) método


Determina si el objeto [Array](../) especificado contiene un elemento que satisface los requisitos del predicado especificado.

```cpp
static bool System::Array<T>::Exists(ArrayPtr<T> arr, std::function<bool(T)> match)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | El array en el que buscar el elemento |
| match | std::function\<**bool**(T)> | Objeto función que define los requisitos y verifica si un elemento los satisface |

### Valor devuelto

Verdadero si **arr** contiene un elemento que satisface los requisitos definidos por **match**

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Clase [Array](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)
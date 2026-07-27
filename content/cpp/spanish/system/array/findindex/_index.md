---
title: FindIndex()
second_title: Referencia de API de Aspose.Slides para C++
description: Busca el primer elemento en la matriz especificada que satisface las condiciones del predicado especificado.
type: docs
weight: 638
url: /es/system/array/findindex/
---
## Array::FindIndex(System::ArrayPtr\<T\>, System::Predicate\<T\>) método


Busca el primer elemento en la matriz especificada que satisfaga las condiciones del predicado especificado.

```cpp
static int System::Array<T>::FindIndex(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) para buscar un elemento en |
| match | [System::Predicate](../../predicate/)\<T\> | Un predicado que define las condiciones para comparar los elementos de la matriz |

### Valor de retorno

El índice del primer elemento en la matriz que satisface las condiciones definidas por el predicado, de lo contrario -1

## Véase también

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Clase [Array](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)
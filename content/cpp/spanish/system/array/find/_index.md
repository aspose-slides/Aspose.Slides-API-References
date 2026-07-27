---
title: Find()
second_title: Referencia de API de Aspose.Slides para C++
description: Busca el primer elemento en la matriz especificada que satisface las condiciones del predicado especificado.
type: docs
weight: 651
url: /es/system/array/find/
---
## Array::Find(System::ArrayPtr\<T\>, System::Predicate\<T\>) método

Busca el primer elemento en la matriz especificada que satisface las condiciones del predicado especificado.

```cpp
static T System::Array<T>::Find(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) para buscar un elemento en |
| match | [System::Predicate](../../predicate/)\<T\> | Un predicado que define las condiciones para coincidir con los elementos de la matriz |

### Valor devuelto

Copia del primer elemento en la matriz que satisface las condiciones definidas por el predicado, de lo contrario valor predeterminado del tipo T

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Clase [Array](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)
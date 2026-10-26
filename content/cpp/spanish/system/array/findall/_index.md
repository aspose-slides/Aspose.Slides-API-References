---
title: FindAll()
second_title: Referencia de API de Aspose.Slides para C++
description: Recupera todos los elementos que coinciden con las condiciones definidas por el predicado especificado.
type: docs
weight: 664
url: /es/system/array/findall/
---
## Array::FindAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) método

Recupera todos los elementos que coinciden con las condiciones definidas por el predicado especificado.

```cpp
static System::ArrayPtr<T> System::Array<T>::FindAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) para buscar elementos en |
| match | [System::Predicate](../../predicate/)\<T\> | Un predicado que define las condiciones para coincidir con los elementos del array |

### Valor devuelto

Un [Array](../) que contiene todos los elementos que coinciden con las condiciones definidas por el predicado especificado, si se encuentran; de lo contrario, un [Array](../) vacío.

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Clase [Array](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)
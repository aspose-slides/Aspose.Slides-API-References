---
title: IsProperSubsetOf()
second_title: Referencia de la API de Aspose.Slides para C++
description: Comprueba si el conjunto actual es un subconjunto estricto de otro contenedor.
type: docs
weight: 40
url: /es/system.collections.generic/iset/ispropersubsetof/
---
## ISet::IsProperSubsetOf(IEnumerablePtr) método

Comprueba si el conjunto actual es un subconjunto estricto de otro contenedor.

```cpp
virtual bool System::Collections::Generic::ISet<T>::IsProperSubsetOf(IEnumerablePtr other)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [IEnumerablePtr](../ienumerableptr/) | Superconjunto contra el cual comprobar. |

### Valor devuelto

True si todos los elementos en el conjunto actual están presentes en **other** y **other** tiene más elementos que el conjunto actual, false en caso contrario.

## Ver también

* Typedef [IEnumerablePtr](../ienumerableptr/)
* Clase [ISet](../)
* Espacio de nombres [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)
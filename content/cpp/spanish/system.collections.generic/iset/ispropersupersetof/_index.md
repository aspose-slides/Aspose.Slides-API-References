---
title: IsProperSupersetOf()
second_title: Referencia de la API de Aspose.Slides para C++
description: Comprueba si el conjunto actual es un superconjunto estricto de otro contenedor.
type: docs
weight: 53
url: /es/system.collections.generic/iset/ispropersupersetof/
---
## ISet::IsProperSupersetOf(IEnumerablePtr) método


Comprueba si el conjunto actual es un superconjunto estricto de otro contenedor.

```cpp
virtual bool System::Collections::Generic::ISet<T>::IsProperSupersetOf(IEnumerablePtr other)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [IEnumerablePtr](../ienumerableptr/) | Subconjunto contra el que se verifica. |

### Valor de retorno

True si todos los elementos en **other** están presentes en el conjunto y el conjunto tiene más elementos que **other**, false en caso contrario.

## Ver también

* Typedef [IEnumerablePtr](../ienumerableptr/)
* Clase [ISet](../)
* Espacio de nombres [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)
---
title: MakeYieldEnumerator()
second_title: Referencia de la API de Aspose.Slides for C++
description: Crea un IEnumerator a partir de una función yield.
type: docs
weight: 2432
url: /es/system/makeyieldenumerator/
---
## System::MakeYieldEnumerator(const Details::YieldFunction\<T\>\&) function


Crea un IEnumerator a partir de una función yield.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerator<T>> System::MakeYieldEnumerator(const Details::YieldFunction<T> &fnc)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en la secuencia |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | La función yield a ejecutar |

### Valor de retorno

Puntero compartido al IEnumerator

## Ver también

* Typedef [SharedPtr](../sharedptr/)
* Clase [IEnumerator](../../system.collections.generic/ienumerator/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)
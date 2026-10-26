---
title: MakeYieldEnumerable()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un IEnumerable a partir de una función de generación.
type: docs
weight: 2419
url: /es/system/makeyieldenumerable/
---
## System::MakeYieldEnumerable(const Details::YieldFunction\<T\>\&) función

Crea un IEnumerable a partir de una función de generación.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerable<T>> System::MakeYieldEnumerable(const Details::YieldFunction<T> &fnc)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de elementos en la secuencia |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | La función de generación a ejecutar |

### Valor devuelto

Puntero compartido a IEnumerable

## Véase también

* Typedef [SharedPtr](../sharedptr/)
* Clase [IEnumerable](../../system.collections.generic/ienumerable/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)
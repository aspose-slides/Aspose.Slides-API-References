---
title: BuildArray()
second_title: Referencia de API de Aspose.Slides para C++
description: Construir una matriz.
type: docs
weight: 2276
url: /es/system/buildarray/
---
## System::BuildArray() función

Construir una matriz.

```cpp
template<typename T> Details::ObjectBuilder<Details::ArrayStorage<T>> System::BuildArray()
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de elemento de la matriz a construir |

### Valor devuelto

ObjectBuilder configurado para la construcción de la matriz

## Observaciones

Crea un ArrayPtr<T> y devuelve un generador para él
[Object](../object/) la construcción debe finalizarse con la llamada [Get()](../get/)

## Véase también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)
---
title: Add()
second_title: Referencia de API de Aspose.Slides para C++
description: Añade los valores de ancho y alto del objeto Size especificado a los valores de coordenadas X e Y del objeto Point especificado, respectivamente.
type: docs
weight: 183
url: /es/system.drawing/point/add/
---
## Point::Add(const Point\&, const Size\&) método


Añade los valores de ancho y alto del objeto [Size](../../size/) especificado a los valores de coordenadas X e Y del objeto [Point](../) especificado, respectivamente.

```cpp
static Point System::Drawing::Point::Add(const Point &point, const Size &size)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | const [Point](../)\& | El punto a trasladar |
| size | const [Size](../../size/)\& | El objeto [Size](../../size/) que especifica los valores a añadir a los valores de coordenadas del **point** |

### Valor de retorno

Un nuevo objeto [Point](../) cuyo valor de coordenada X es igual a la suma del valor de coordenada X del **point** y el valor de ancho del **size**, y cuyo valor de coordenada Y es igual a la suma del valor de coordenada Y del **point** y el valor de alto del **size**

## Ver también

* Clase [Point](../)
* Clase [Size](../../size/)
* Espacio de nombres [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)
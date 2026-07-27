---
title: Subtract()
second_title: Referencia de API de Aspose.Slides para C++
description: Resta los valores de ancho y alto del objeto Size especificado de los valores de coordenadas X y Y del objeto Point especificado correspondientemente.
type: docs
weight: 196
url: /es/system.drawing/point/subtract/
---
## Point::Subtract(const Point\&, const Size\&) método

Resta los valores de ancho y alto del objeto [Size](../../size/) especificado de los valores de coordenadas X y Y del objeto [Point](../) especificado correspondientemente.

```cpp
static Point System::Drawing::Point::Subtract(const Point &point, const Size &size)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | const [Point](../)\& | El punto a trasladar |
| size | const [Size](../../size/)\& | El objeto [Size](../../size/) que especifica los valores que se restarán de los valores de coordenadas del **point** |

### Valor devuelto

Un nuevo objeto [Point](../) cuyo valor de coordenada X es igual al resultado de la resta del valor de ancho de **size** al valor de coordenada X de **point** y cuyo valor de coordenada Y es igual al resultado de la resta del valor de alto de **size** al valor de coordenada Y de **point**.

## Ver también

* Clase [Point](../)
* Clase [Size](../../size/)
* Espacio de nombres [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)
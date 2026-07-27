---
title: Add()
second_title: Referencia de la API de Aspose.Slides para C++
description: Agrega los valores de ancho y alto del objeto SizeF especificado a los valores de coordenadas X y Y del objeto PointF especificado correspondientemente.
type: docs
weight: 144
url: /es/system.drawing/pointf/add/
---
## PointF::Add(const PointF\&, const SizeF\&) método


Agrega los valores de ancho y alto del objeto [SizeF](../../sizef/) especificado a los valores de coordenadas X y Y del objeto [PointF](../) especificado correspondientemente.

```cpp
static PointF System::Drawing::PointF::Add(const PointF &point, const SizeF &size)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | const [PointF](../)\& | El punto a trasladar |
| size | const [SizeF](../../sizef/)\& | El objeto [SizeF](../../sizef/) que especifica los valores a agregar a los valores de coordenadas del **point** |

### Valor de retorno

Un nuevo objeto [PointF](../) cuyo valor de coordenada X es igual a la suma del valor de coordenada X de **point** y el valor de ancho de **size**, y cuyo valor de coordenada Y es igual a la suma del valor de coordenada Y de **point** y el valor de altura de **size**.

## PointF::Add(const PointF\&, const Size\&) método


Agrega los valores de ancho y alto del objeto [Size](../../size/) especificado a los valores de coordenadas X y Y del objeto [PointF](../) especificado correspondientemente.

```cpp
static PointF System::Drawing::PointF::Add(const PointF &point, const Size &size)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | const [PointF](../)\& | El punto a trasladar |
| size | const [Size](../../size/)\& | El objeto [Size](../../size/) que especifica los valores a agregar a los valores de coordenadas del **point** |

### Valor de retorno

Un nuevo objeto [PointF](../) cuyo valor de coordenada X es igual a la suma del valor de coordenada X de **point** y el valor de ancho de **size**, y cuyo valor de coordenada Y es igual a la suma del valor de coordenada Y de **point** y el valor de altura de **size**.

## Ver también

* Clase [PointF](../)
* Clase [SizeF](../../sizef/)
* Clase [Size](../../size/)
* Espacio de nombres [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)
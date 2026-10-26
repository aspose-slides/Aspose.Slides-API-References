---
title: Subtract()
second_title: Referencia de la API de Aspose.Slides para C++
description: Resta los valores de ancho y alto del objeto SizeF especificado a los valores de coordenadas X e Y del objeto PointF especificado, correspondientemente.
type: docs
weight: 157
url: /es/system.drawing/pointf/subtract/
---
## PointF::Subtract(const PointF\&, const SizeF\&) método

Resta los valores de ancho y alto del objeto [SizeF](../../sizef/) especificado a los valores de coordenadas X e Y del objeto [PointF](../) especificado, correspondientemente.

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const SizeF &size)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | const [PointF](../)\& | El punto a traducir |
| size | const [SizeF](../../sizef/)\& | El objeto [SizeF](../../sizef/) que especifica los valores a restar de los valores de coordenadas del **point** |

### Valor devuelto

Un nuevo objeto [PointF](../) cuyo valor de coordenada X es igual al resultado de la resta del valor de ancho de **size** del valor de coordenada X de **point** y cuyo valor de coordenada Y es igual al resultado de la resta del valor de alto de **size** del valor de coordenada Y de **point**

## PointF::Subtract(const PointF\&, const Size\&) método

Resta los valores de ancho y alto del objeto [Size](../../size/) especificado a los valores de coordenadas X e Y del objeto [PointF](../) especificado, correspondientemente.

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const Size &size)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | const [PointF](../)\& | El punto a traducir |
| size | const [Size](../../size/)\& | El objeto [Size](../../size/) que especifica los valores a restar de los valores de coordenadas del **point** |

### Valor devuelto

Un nuevo objeto [PointF](../) cuyo valor de coordenada X es igual al resultado de la resta del valor de ancho de **size** del valor de coordenada X de **point** y cuyo valor de coordenada Y es igual al resultado de la resta del valor de alto de **size** del valor de coordenada Y de **point**

## Ver también

* Clase [PointF](../)
* Clase [SizeF](../../sizef/)
* Clase [Size](../../size/)
* Espacio de nombres [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)
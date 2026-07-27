---
title: Inflate()
second_title: Referencia de API de Aspose.Slides para C++
description: Incrementa el ancho y la altura del rectángulo representado por el objeto actual, manteniendo la ubicación del centro geométrico del rectángulo. El ancho y la altura se incrementan en ambas direcciones por las cantidades especificadas.
type: docs
weight: 261
url: /es/system.drawing/rectanglef/inflate/
---
## RectangleF::Inflate(float, float) método

Incrementa el ancho y la altura del rectángulo representado por el objeto actual, manteniendo la ubicación del centro geométrico del rectángulo. El ancho y la altura se incrementan en ambas direcciones por las cantidades especificadas.

```cpp
void System::Drawing::RectangleF::Inflate(float width, float height)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | **float** | La cantidad en que se debe incrementar el ancho del rectángulo en ambas direcciones |
| height | **float** | La cantidad en que se debe incrementar la altura del rectángulo en ambas direcciones |

## RectangleF::Inflate(const SizeF\&) método

Incrementa el ancho y la altura del rectángulo representado por el objeto actual, manteniendo la ubicación del centro geométrico del rectángulo. El ancho y la altura se incrementan en ambas direcciones por las cantidades especificadas por los valores de ancho y altura del objeto size especificado, respectivamente.

```cpp
void System::Drawing::RectangleF::Inflate(const SizeF &size)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | const [SizeF](../../sizef/)\& | El objeto [SizeF](../../sizef/) que especifica las cantidades para incrementar el ancho y la altura del rectángulo |

## RectangleF::Inflate(const RectangleF\&, float, float) método

Incrementa el ancho y la altura del rectángulo representado por el objeto especificado, manteniendo la ubicación del centro geométrico del rectángulo. El ancho y la altura se incrementan en ambas direcciones por las cantidades especificadas.

```cpp
static RectangleF System::Drawing::RectangleF::Inflate(const RectangleF &rect, float x, float y)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | const [RectangleF](../)\& | Un rectángulo para inflar |
| x | **float** | La cantidad en que se debe incrementar el ancho del rectángulo en ambas direcciones |
| y | **float** | La cantidad en que se debe incrementar la altura del rectángulo en ambas direcciones |

### Valor devuelto

El objeto [RectangleF](../) que representa el rectángulo ampliado

## Véase también

* Clase [RectangleF](../)
* Clase [SizeF](../../sizef/)
* Espacio de nombres [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)
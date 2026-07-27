---
title: Union()
second_title: Referencia de API de Aspose.Slides para C++
description: Reemplaza la región representada por el objeto actual con el resultado de la operación de unión de esta región y una región definida por el rectángulo especificado.
type: docs
weight: 53
url: /es/system.drawing/region/union/
---
## Region::Union(const RectangleF\&) método

Reemplaza la región representada por el objeto actual con el resultado de la operación de unión de esta región y una región definida por el rectángulo especificado.

```cpp
void System::Drawing::Region::Union(const RectangleF &rect)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Un rectángulo que define una región para unir con esta región |

## Region::Union(const Rectangle\&) método

Reemplaza la región representada por el objeto actual con el resultado de la unión de esta región y una región definida por el rectángulo especificado.

```cpp
void System::Drawing::Region::Union(const Rectangle &rect)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Un rectángulo que define una región para unir con esta región |

## Region::Union(const SharedPtr\<Drawing2D::GraphicsPath\>\&) método

Reemplaza la región representada por el objeto actual con el resultado de la unión de esta región y una región definida por la ruta especificada.

```cpp
void System::Drawing::Region::Union(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Una ruta que define una región para unir con esta región |

## Region::Union(const SharedPtr\<Region\>\&) método

Reemplaza la región representada por el objeto actual con el resultado de la unión de esta región y la región especificada.

```cpp
void System::Drawing::Region::Union(const SharedPtr<Region> &region)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Una región para unir con esta región |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [RectangleF](../../rectanglef/)
* Clase [Region](../)
* Clase [Rectangle](../../rectangle/)
* Clase [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Espacio de nombres [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)
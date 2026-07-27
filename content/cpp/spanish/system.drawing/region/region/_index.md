---
title: Region()
second_title: Referencia de la API de Aspose.Slides para C++
description: Construye una nueva instancia de la clase Region.
type: docs
weight: 1
url: /es/system.drawing/region/region/
---
## Region::Region() constructor

Construye una nueva instancia de la clase [Region](../).

```cpp
System::Drawing::Region::Region()
```

## Region::Region(const RectangleF\&) constructor

Construye una nueva instancia de la clase [Region](../) que representa una región definida por el rectángulo especificado.

```cpp
System::Drawing::Region::Region(const RectangleF &rect)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Un rectángulo que define la región |

## Region::Region(const Rectangle\&) constructor

Construye una nueva instancia de la clase [Region](../) que representa una región definida por el rectángulo especificado.

```cpp
System::Drawing::Region::Region(const Rectangle &rect)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Un rectángulo que define la región |

## Region::Region(const SharedPtr\<Drawing2D::GraphicsPath\>\&) constructor

Construye una nueva instancia de la clase [Region](../) que representa una región definida por la ruta especificada.

```cpp
System::Drawing::Region::Region(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Una ruta que define la región |

## Region::Region(const SkPath\&) constructor

```cpp
System::Drawing::Region::Region(const SkPath &path)
```

## Region::Region(const SharedPtr\<Drawing2D::RegionData\>\&) constructor

Construye una nueva instancia de la clase [Region](../) que representa una región definida por el objeto RegionData especificado.

```cpp
System::Drawing::Region::Region(const SharedPtr<Drawing2D::RegionData> &region_data)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| region_data | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::RegionData](../../../system.drawing.drawing2d/regiondata/)\>\& | Un objeto RegionData que define la región |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Region](../)
* Clase [RectangleF](../../rectanglef/)
* Clase [Rectangle](../../rectangle/)
* Clase [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Clase [RegionData](../../../system.drawing.drawing2d/regiondata/)
* Espacio de nombres [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)
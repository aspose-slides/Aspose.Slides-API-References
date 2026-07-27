---
title: GraphicsPath()
second_title: Referencia de la API de Aspose.Slides para C++
description: Construye una nueva instancia de la clase GraphicsPath con el modo de relleno especificado.
type: docs
weight: 1
url: /es/system.drawing.drawing2d/graphicspath/graphicspath/
---
## GraphicsPath::GraphicsPath(FillMode) constructor


Construye una nueva instancia de la clase [GraphicsPath](../) con el modo de relleno especificado.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(FillMode fillMode=FillMode::Alternate)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fillMode | [FillMode](../../fillmode/) | Especifica cómo se debe rellenar el interior del camino cerrado representado por el objeto que se está creando |

## GraphicsPath::GraphicsPath(const ArrayPtr\<Point\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) constructor


Construye una nueva instancia del objeto [GraphicsPath](../) que representa la ruta especificada.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<Point> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Una matriz que contiene los puntos que especifican la ruta a representar por el objeto que se está creando |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Una matriz que contiene los valores que especifican los tipos de los puntos correspondientes en la matriz **pts** |
| fillMode | [FillMode](../../fillmode/) | Especifica cómo se debe rellenar el interior del camino cerrado representado por el objeto que se está creando |

## GraphicsPath::GraphicsPath(const ArrayPtr\<PointF\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) constructor


Construye una nueva instancia del objeto [GraphicsPath](../) que representa la ruta especificada.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<PointF> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Una matriz que contiene los puntos que especifican la ruta a representar por el objeto que se está creando |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Una matriz que contiene los valores que especifican los tipos de los puntos correspondientes en la matriz **pts** |
| fillMode | [FillMode](../../fillmode/) | Especifica cómo se debe rellenar el interior del camino cerrado representado por el objeto que se está creando |

## GraphicsPath::GraphicsPath(const SkPath\&) constructor




```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const SkPath &path)
```

## Ver también

* Enum [FillMode](../../fillmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [GraphicsPath](../)
* Class [Point](../../../system.drawing/point/)
* Class [PointF](../../../system.drawing/pointf/)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)
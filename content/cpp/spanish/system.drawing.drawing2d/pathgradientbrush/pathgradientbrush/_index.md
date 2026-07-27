---
title: PathGradientBrush()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye una nueva instancia de la clase PathGradientBrush.
type: docs
weight: 1
url: /es/system.drawing.drawing2d/pathgradientbrush/pathgradientbrush/
---
## PathGradientBrush::PathGradientBrush(const ArrayPtr\<PointF\>\&, WrapMode) constructor


Construye una nueva instancia de la clase [PathGradientBrush](../).

```cpp
System::Drawing::Drawing2D::PathGradientBrush::PathGradientBrush(const ArrayPtr<PointF> &points, WrapMode wrapMode=WrapMode::Clamp)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Una matriz que contiene los vértices de la ruta |
| wrapMode | [WrapMode](../../wrapmode/) | Especifica cómo se deben mosaicar los rellenos dibujados por un pincel representado por el objeto que se está creando |

## PathGradientBrush::PathGradientBrush(const ArrayPtr\<Point\>\&, WrapMode) constructor


Construye una nueva instancia de la clase [PathGradientBrush](../).

```cpp
System::Drawing::Drawing2D::PathGradientBrush::PathGradientBrush(const ArrayPtr<Point> &points, WrapMode wrapMode=WrapMode::Clamp)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Una matriz que contiene los vértices de la ruta |
| wrapMode | [WrapMode](../../wrapmode/) | Especifica cómo se deben mosaicar los rellenos dibujados por un pincel representado por el objeto que se está creando |

## PathGradientBrush::PathGradientBrush(const SharedPtr\<GraphicsPath\>\&) constructor


Construye una nueva instancia de la clase [PathGradientBrush](../).

```cpp
System::Drawing::Drawing2D::PathGradientBrush::PathGradientBrush(const SharedPtr<GraphicsPath> &path)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Un objeto [GraphicsPath](../../graphicspath/) que especifica una ruta rellena por el objeto que se está creando |

## Ver también

* Enum [WrapMode](../../wrapmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [PathGradientBrush](../)
* Class [Point](../../../system.drawing/point/)
* Class [GraphicsPath](../../graphicspath/)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)
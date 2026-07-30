---
title: PathGradientBrush()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova istanza della classe PathGradientBrush.
type: docs
weight: 1
url: /it/system.drawing.drawing2d/pathgradientbrush/pathgradientbrush/
---
## PathGradientBrush::PathGradientBrush(const ArrayPtr\<PointF\>\&, WrapMode) costruttore

Crea una nuova istanza della classe [PathGradientBrush](../).

```cpp
System::Drawing::Drawing2D::PathGradientBrush::PathGradientBrush(const ArrayPtr<PointF> &points, WrapMode wrapMode=WrapMode::Clamp)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | An array that contains vertices of the path |
| wrapMode | [WrapMode](../../wrapmode/) | Specifies how the fills drawn by a brush represented by the object being created should be tiled |

## PathGradientBrush::PathGradientBrush(const ArrayPtr\<Point\>\&, WrapMode) costruttore

Crea una nuova istanza della classe [PathGradientBrush](../).

```cpp
System::Drawing::Drawing2D::PathGradientBrush::PathGradientBrush(const ArrayPtr<Point> &points, WrapMode wrapMode=WrapMode::Clamp)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | An array that contains vertices of the path |
| wrapMode | [WrapMode](../../wrapmode/) | Specifies how the fills drawn by a brush represented by the object being created should be tiled |

## PathGradientBrush::PathGradientBrush(const SharedPtr\<GraphicsPath\>\&) costruttore

Crea una nuova istanza della classe [PathGradientBrush](../).

```cpp
System::Drawing::Drawing2D::PathGradientBrush::PathGradientBrush(const SharedPtr<GraphicsPath> &path)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Un oggetto [GraphicsPath](../../graphicspath/) che specifica un percorso riempito dall'oggetto creato |

## Vedi anche

* Enum [WrapMode](../../wrapmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [PointF](../../../system.drawing/pointf/)
* Classe [PathGradientBrush](../)
* Classe [Point](../../../system.drawing/point/)
* Classe [GraphicsPath](../../graphicspath/)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)
---
title: FillClosedCurve()
second_title: Riferimento API di Aspose.Slides per C++
description: Disegna una spline chiusa usando il brush specificato.
type: docs
weight: 807
url: /it/system.drawing/graphics/fillclosedcurve/
---
## Graphics::FillClosedCurve(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode, float) method

Disegna una spline chiusa usando il brush specificato.

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Un brush da usare quando si disegna la spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) di punti che determinano la spline |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | IGNORED |
| tension | **float** | Valore che specifica la tensione della spline |

## Graphics::FillClosedCurve(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode, float) method

Disegna una spline chiusa usando il brush specificato.

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Un brush da usare quando si disegna la spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) di punti che determinano la spline |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | IGNORED |
| tension | **float** | Valore che specifica la tensione della spline |

## Vedi anche

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Brush](../../brush/)
* Class [PointF](../../pointf/)
* Class [Graphics](../)
* Class [Point](../../point/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
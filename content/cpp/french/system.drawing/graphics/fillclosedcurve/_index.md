---
title: FillClosedCurve()
second_title: Référence de l'API Aspose.Slides pour C++
description: Dessine une spline fermée en utilisant le pinceau spécifié.
type: docs
weight: 807
url: /fr/system.drawing/graphics/fillclosedcurve/
---
## Graphics::FillClosedCurve(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode, float) method

Dessine une spline fermée en utilisant le pinceau spécifié.

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Un pinceau à utiliser lors du dessin de la spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) de points qui déterminent la spline |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | IGNORÉ |
| tension | **float** | Valeur qui spécifie la tension de la spline |

## Graphics::FillClosedCurve(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode, float) method

Dessine une spline fermée en utilisant le pinceau spécifié.

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Un pinceau à utiliser lors du dessin de la spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) de points qui déterminent la spline |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | IGNORÉ |
| tension | **float** | Valeur qui spécifie la tension de la spline |

## Voir aussi

* Énum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Brush](../../brush/)
* Classe [PointF](../../pointf/)
* Classe [Graphics](../)
* Classe [Point](../../point/)
* Espace de noms [System::Drawing](../../)
* Bibliothèque [Aspose.Slides](../../../)
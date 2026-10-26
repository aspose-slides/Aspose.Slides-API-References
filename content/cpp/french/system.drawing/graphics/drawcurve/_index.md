---
title: DrawCurve()
second_title: Référence API Aspose.Slides pour C++
description: Dessine une spline en utilisant le stylo spécifié.
type: docs
weight: 794
url: /fr/system.drawing/graphics/drawcurve/
---
## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float) méthode

Dessine une spline en utilisant le pen spécifié.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Un pen à utiliser lors du dessin de la spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) de points qui déterminent la spline |
| tension | **float** | Valeur qui spécifie la tension de la spline |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float) méthode

Dessine une spline en utilisant le pen spécifié.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Un pen à utiliser lors du dessin de la spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) de points qui déterminent la spline |
| tension | **float** | Valeur qui spécifie la tension de la spline |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, int32_t, int32_t, float) méthode

Dessine une spline en utilisant le pen spécifié.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Un pen à utiliser lors du dessin de la spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) de points qui déterminent la spline |
| offset | **int32_t** | Décalage à partir du 1er élément du tableau **points** |
| numberOfSegments | **int32_t** | Nombre de segments à inclure dans la courbe |
| tension | **float** | Valeur qui spécifie la tension de la spline |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, int32_t, int32_t, float) méthode

Dessine une spline en utilisant le pen spécifié.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Un pen à utiliser lors du dessin de la spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) de points qui déterminent la spline |
| offset | **int32_t** | Décalage à partir du 1er élément du tableau **points** |
| numberOfSegments | **int32_t** | Nombre de segments à inclure dans la courbe |
| tension | **float** | Valeur qui spécifie la tension de la spline |

## Voir Aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Pen](../../pen/)
* Classe [Point](../../point/)
* Classe [Graphics](../)
* Classe [PointF](../../pointf/)
* Espace de noms [System::Drawing](../../)
* Bibliothèque [Aspose.Slides](../../../)
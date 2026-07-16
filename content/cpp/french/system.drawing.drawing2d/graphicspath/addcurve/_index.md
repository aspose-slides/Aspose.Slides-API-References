---
title: AddCurve()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute la courbe spécifiée au chemin représenté par l'objet actuel.
type: docs
weight: 274
url: /fr/system.drawing.drawing2d/graphicspath/addcurve/
---
## GraphicsPath::AddCurve(const ArrayPtr\<PointF\>\&, float) méthode

Ajoute la courbe spécifiée au chemin représenté par l'objet actuel.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<PointF> &points, float tension=0.5)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Les points qui définissent la courbe |
| tension | **float** | Spécifie la quantité que la courbe se plie entre les points de contrôle |

## GraphicsPath::AddCurve(const ArrayPtr\<Point\>\&, float) méthode

Ajoute la courbe spécifiée au chemin représenté par l'objet actuel.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<Point> &points, float tension=0.5)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Les points qui définissent la courbe |
| tension | **float** | Spécifie la quantité que la courbe se plie entre les points de contrôle |

## GraphicsPath::AddCurve(const ArrayPtr\<PointF\>\&, int, int, float) méthode

Ajoute la courbe spécifiée au chemin représenté par l'objet actuel.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<PointF> &points, int offset, int number_of_segments, float tension)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Les points qui définissent la courbe |
| offset | int | L'index du point dans **points** qui est utilisé comme point de départ de la courbe |
| number_of_segments | int | Le nombre de segments utilisés pour tracer la courbe |
| tension | **float** | Spécifie la quantité que la courbe se plie entre les points de contrôle |

## GraphicsPath::AddCurve(const ArrayPtr\<Point\>\&, int, int, float) méthode

Ajoute la courbe spécifiée au chemin représenté par l'objet actuel.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<Point> &points, int offset, int number_of_segments, float tension)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Les points qui définissent la courbe |
| offset | int | L'index du point dans **points** qui est utilisé comme point de départ de la courbe |
| number_of_segments | int | Le nombre de segments utilisés pour tracer la courbe |
| tension | **float** | Spécifie la quantité que la courbe se plie entre les points de contrôle |

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [PointF](../../../system.drawing/pointf/)
* Classe [GraphicsPath](../)
* Classe [Point](../../../system.drawing/point/)
* Espace de noms [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)
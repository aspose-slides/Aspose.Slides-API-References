---
title: CubicBezierTo()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute une courbe de Bézier cubique à la fin du chemin
type: docs
weight: 92
url: /fr/aspose.slides/igeometrypath/cubicbezierto/
---
## IGeometryPath::CubicBezierTo(System::Drawing::PointF, System::Drawing::PointF, System::Drawing::PointF) method


Ajoute une courbe de Bézier cubique à la fin du chemin

```cpp
virtual void Aspose::Slides::IGeometryPath::CubicBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, System::Drawing::PointF point3)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | First direction point |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Second direction point |
| point3 | [System::Drawing::PointF](../../../system.drawing/pointf/) | End point |

## IGeometryPath::CubicBezierTo(float, float, float, float, float, float) method


Ajoute une courbe de Bézier cubique à la fin du chemin

```cpp
virtual void Aspose::Slides::IGeometryPath::CubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x1 | **float** | X coordinate of first direction point |
| y1 | **float** | Y coordinate of first direction point |
| x2 | **float** | X coordinate of second direction point |
| y2 | **float** | Y coordinate of second direction point |
| x3 | **float** | X coordinate of end point |
| y3 | **float** | Y coordinate of end point |

## IGeometryPath::CubicBezierTo(System::Drawing::PointF, System::Drawing::PointF, System::Drawing::PointF, uint32_t) method


Ajoute une courbe de Bézier cubique à l'emplacement spécifié du chemin

```cpp
virtual void Aspose::Slides::IGeometryPath::CubicBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, System::Drawing::PointF point3, uint32_t index)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | First direction point |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Second direction point |
| point3 | [System::Drawing::PointF](../../../system.drawing/pointf/) | End point |
| index | **uint32_t** | Index of segment in PathData |

## IGeometryPath::CubicBezierTo(float, float, float, float, float, float, uint32_t) method


Ajoute une courbe de Bézier cubique à l'emplacement spécifié du chemin

```cpp
virtual void Aspose::Slides::IGeometryPath::CubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, uint32_t index)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x1 | **float** | X coordinate of first direction point |
| y1 | **float** | Y coordinate of first direction point |
| x2 | **float** | X coordinate of second direction point |
| y2 | **float** | Y coordinate of second direction point |
| x3 | **float** | X coordinate of end point |
| y3 | **float** | Y coordinate of end point |
| index | **uint32_t** | Index of segment in PathData |

## Voir aussi

* Classe [PointF](../../../system.drawing/pointf/)
* Classe [IGeometryPath](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
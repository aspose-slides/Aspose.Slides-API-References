---
title: QuadraticBezierTo()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute une courbe de Bézier quadratique à la fin du chemin
type: docs
weight: 105
url: /fr/aspose.slides/igeometrypath/quadraticbezierto/
---
## IGeometryPath::QuadraticBezierTo(System::Drawing::PointF, System::Drawing::PointF) méthode


Ajoute une courbe de Bézier quadratique à la fin du chemin

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Point de direction |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Point d'extrémité |

## IGeometryPath::QuadraticBezierTo(float, float, float, float) méthode


Ajoute une courbe de Bézier quadratique à la fin du chemin

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(float x1, float y1, float x2, float y2)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x1 | **float** | Coordonnée X du point de direction |
| y1 | **float** | Coordonnée Y du point de direction |
| x2 | **float** | Coordonnée X du point d'extrémité |
| y2 | **float** | Coordonnée Y du point d'extrémité |

## IGeometryPath::QuadraticBezierTo(System::Drawing::PointF, System::Drawing::PointF, uint32_t) méthode


Ajoute une courbe de Bézier quadratique à l'emplacement spécifié du chemin

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, uint32_t index)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Point de direction |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Point d'extrémité |
| index | **uint32_t** | Index du segment dans PathData |

## IGeometryPath::QuadraticBezierTo(float, float, float, float, uint32_t) méthode


Ajoute une courbe de Bézier quadratique à l'emplacement spécifié du chemin

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(float x1, float y1, float x2, float y2, uint32_t index)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x1 | **float** | Coordonnée X du point de direction |
| y1 | **float** | Coordonnée Y du point de direction |
| x2 | **float** | Coordonnée X du point d'extrémité |
| y2 | **float** | Coordonnée Y du point d'extrémité |
| index | **uint32_t** | Index du segment dans PathData |

## Voir aussi

* Classe [PointF](../../../system.drawing/pointf/)
* Classe [IGeometryPath](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
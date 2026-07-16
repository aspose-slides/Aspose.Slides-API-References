---
title: CubicBezierTo()
second_title: Référence API Aspose.Slides pour C++
description: Ajoute une courbe de Bézier cubique à la fin du chemin
type: docs
weight: 105
url: /fr/aspose.slides/geometrypath/cubicbezierto/
---
## GeometryPath::CubicBezierTo(System::Drawing::PointF, System::Drawing::PointF, System::Drawing::PointF) méthode

Ajoute une courbe de Bézier cubique à la fin du chemin

```cpp
void Aspose::Slides::GeometryPath::CubicBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, System::Drawing::PointF point3) override
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Premier point de direction |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Deuxième point de direction |
| point3 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Point final |

## GeometryPath::CubicBezierTo(float, float, float, float, float, float) méthode

Ajoute une courbe de Bézier cubique à la fin du chemin

```cpp
void Aspose::Slides::GeometryPath::CubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) override
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| x1 | **float** | Coordonnée X du premier point de direction |
| y1 | **float** | Coordonnée Y du premier point de direction |
| x2 | **float** | Coordonnée X du deuxième point de direction |
| y2 | **float** | Coordonnée Y du deuxième point de direction |
| x3 | **float** | Coordonnée X du point final |
| y3 | **float** | Coordonnée Y du point final |

## GeometryPath::CubicBezierTo(System::Drawing::PointF, System::Drawing::PointF, System::Drawing::PointF, uint32_t) méthode

Ajoute une courbe de Bézier cubique à l'emplacement spécifié du chemin

```cpp
void Aspose::Slides::GeometryPath::CubicBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, System::Drawing::PointF point3, uint32_t index) override
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Premier point de direction |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Deuxième point de direction |
| point3 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Point final |
| index | **uint32_t** | Indice du segment dans PathData |

## GeometryPath::CubicBezierTo(float, float, float, float, float, float, uint32_t) méthode

Ajoute une courbe de Bézier cubique à l'emplacement spécifié du chemin

```cpp
void Aspose::Slides::GeometryPath::CubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, uint32_t index) override
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| x1 | **float** | Coordonnée X du premier point de direction |
| y1 | **float** | Coordonnée Y du premier point de direction |
| x2 | **float** | Coordonnée X du deuxième point de direction |
| y2 | **float** | Coordonnée Y du deuxième point de direction |
| x3 | **float** | Coordonnée X du point final |
| y3 | **float** | Coordonnée Y du point final |
| index | **uint32_t** | Indice du segment dans PathData |

## Voir aussi

* Classe [PointF](../../../system.drawing/pointf/)
* Classe [GeometryPath](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)
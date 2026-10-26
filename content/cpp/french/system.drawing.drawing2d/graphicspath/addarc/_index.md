---
title: AddArc()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute l'arc elliptique spécifié au chemin représenté par l'objet actuel.
type: docs
weight: 183
url: /fr/system.drawing.drawing2d/graphicspath/addarc/
---
## GraphicsPath::AddArc(float, float, float, float, float, float) méthode

Ajoute l'arc elliptique spécifié au chemin représenté par l'objet actuel.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | **float** | La coordonnée X du coin supérieur gauche du rectangle qui délimite l'ellipse dont l'arc est tracé |
| y | **float** | La coordonnée Y du coin supérieur gauche du rectangle qui délimite l'ellipse dont l'arc est tracé |
| width | **float** | La largeur du rectangle qui délimite l'ellipse dont l'arc est tracé |
| height | **float** | La hauteur du rectangle qui délimite l'ellipse dont l'arc est tracé |
| startAngle | **float** | Spécifie l'angle de départ de l'arc en degrés, mesuré dans le sens des aiguilles d'une montre à partir de l'axe X |
| sweepAngle | **float** | Spécifie l'angle entre l'angle de départ et la fin de l'arc |

## GraphicsPath::AddArc(int, int, int, int, float, float) méthode

Ajoute l'arc elliptique spécifié au chemin représenté par l'objet actuel.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(int x, int y, int width, int height, float startAngle, float sweepAngle)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée X du coin supérieur gauche du rectangle qui délimite l'ellipse dont l'arc est tracé |
| y | int | La coordonnée Y du coin supérieur gauche du rectangle qui délimite l'ellipse dont l'arc est tracé |
| width | int | La largeur du rectangle qui délimite l'ellipse dont l'arc est tracé |
| height | int | La hauteur du rectangle qui délimite l'ellipse dont l'arc est tracé |
| startAngle | **float** | Spécifie l'angle de départ de l'arc en degrés, mesuré dans le sens des aiguilles d'une montre à partir de l'axe X |
| sweepAngle | **float** | Spécifie l'angle entre l'angle de départ et la fin de l'arc |

## GraphicsPath::AddArc(const RectangleF\&, float, float) méthode

Ajoute l'arc elliptique spécifié au chemin représenté par l'objet actuel.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(const RectangleF &rect, float startAngle, float sweepAngle)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | const [RectangleF](../../../system.drawing/rectanglef/)\& | Le rectangle qui délimite l'ellipse dont l'arc est tracé |
| startAngle | **float** | Spécifie l'angle de départ de l'arc en degrés, mesuré dans le sens des aiguilles d'une montre à partir de l'axe X |
| sweepAngle | **float** | Spécifie l'angle entre l'angle de départ et la fin de l'arc |

## GraphicsPath::AddArc(const Rectangle\&, float, float) méthode

Ajoute l'arc elliptique spécifié au chemin représenté par l'objet actuel.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(const Rectangle &rect, float startAngle, float sweepAngle)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../../system.drawing/rectangle/)\& | Le rectangle qui délimite l'ellipse dont l'arc est tracé |
| startAngle | **float** | Spécifie l'angle de départ de l'arc en degrés, mesuré dans le sens des aiguilles d'une montre à partir de l'axe X |
| sweepAngle | **float** | Spécifie l'angle entre l'angle de départ et la fin de l'arc |

## Voir aussi

* Classe [GraphicsPath](../)
* Classe [RectangleF](../../../system.drawing/rectanglef/)
* Classe [Rectangle](../../../system.drawing/rectangle/)
* Espace de noms [System::Drawing::Drawing2D](../../)
* Bibliothèque [Aspose.Slides](../../../)
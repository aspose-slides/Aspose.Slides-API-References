---
title: AddPie()
second_title: Référence API Aspose.Slides pour C++
description: Ajoute le contour spécifié de la forme de secteur au chemin représenté par l'objet actuel.
type: docs
weight: 209
url: /fr/system.drawing.drawing2d/graphicspath/addpie/
---
## GraphicsPath::AddPie(float, float, float, float, float, float) méthode

Ajoute le contour spécifié de la forme de secteur au chemin représenté par l'objet actuel.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | **float** | La coordonnée X du coin supérieur gauche du rectangle qui délimite l'ellipse dont provient le secteur |
| y | **float** | La coordonnée Y du coin supérieur gauche du rectangle qui délimite l'ellipse dont provient le secteur |
| width | **float** | La largeur du coin supérieur gauche du rectangle qui délimite l'ellipse dont provient le secteur |
| height | **float** | La hauteur du coin supérieur gauche du rectangle qui délimite l'ellipse dont provient le secteur |
| startAngle | **float** | Spécifie l'angle de départ du secteur en degrés, mesuré dans le sens horaire à partir de l'axe X |
| sweepAngle | **float** | Spécifie l'angle entre l'angle de départ et la fin du secteur |

## GraphicsPath::AddPie(int, int, int, int, float, float) méthode

Ajoute le contour spécifié de la forme de secteur au chemin représenté par l'objet actuel.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(int x, int y, int width, int height, float startAngle, float sweepAngle)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée X du coin supérieur gauche du rectangle qui délimite l'ellipse dont provient le secteur |
| y | int | La coordonnée Y du coin supérieur gauche du rectangle qui délimite l'ellipse dont provient le secteur |
| width | int | La largeur du coin supérieur gauche du rectangle qui délimite l'ellipse dont provient le secteur |
| height | int | La hauteur du coin supérieur gauche du rectangle qui délimite l'ellipse dont provient le secteur |
| startAngle | **float** | Spécifie l'angle de départ du secteur en degrés, mesuré dans le sens horaire à partir de l'axe X |
| sweepAngle | **float** | Spécifie l'angle entre l'angle de départ et la fin du secteur |

## GraphicsPath::AddPie(const Rectangle\&, float, float) méthode

Ajoute le contour spécifié de la forme de secteur au chemin représenté par l'objet actuel.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(const Rectangle &rect, float startAngle, float sweepAngle)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../../system.drawing/rectangle/)\& | Le rectangle qui délimite l'ellipse dont provient le secteur |
| startAngle | **float** | Spécifie l'angle de départ du secteur en degrés, mesuré dans le sens horaire à partir de l'axe X |
| sweepAngle | **float** | Spécifie l'angle entre l'angle de départ et la fin du secteur |

## Voir aussi

* Classe [GraphicsPath](../)
* Classe [Rectangle](../../../system.drawing/rectangle/)
* Espace de noms [System::Drawing::Drawing2D](../../)
* Bibliothèque [Aspose.Slides](../../../)
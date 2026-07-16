---
title: Matrix()
second_title: Référence API Aspose.Slides pour C++
description: Construit une nouvelle instance de la classe Matrix qui représente une matrice identité.
type: docs
weight: 1
url: /fr/system.drawing.drawing2d/matrix/matrix/
---
## Matrix::Matrix() constructeur


Construit une nouvelle instance de la classe [Matrix](../) qui représente une matrice identité.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix()
```

## Matrix::Matrix(float, float, float, float, float, float) constructeur


Construit une nouvelle instance de la classe [Matrix](../) et l'initialise avec les valeurs spécifiées.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| m11 | **float** | La valeur de la première ligne première colonne |
| m12 | **float** | La valeur de la première ligne deuxième colonne |
| m21 | **float** | La valeur de la deuxième ligne première colonne |
| m22 | **float** | La valeur de la deuxième ligne deuxième colonne |
| dx | **float** | La valeur de la troisième ligne première colonne |
| dy | **float** | La valeur de la troisième ligne deuxième colonne |

## Matrix::Matrix(const Rectangle\&, const ArrayPtr\<Point\>\&) constructeur


Construit une nouvelle instance de la classe [Matrix](../) à la transformation géométrique définie par le rectangle et le tableau de points spécifiés.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const Rectangle &rect, const ArrayPtr<Point> &plgpts)
```

## Matrix::Matrix(const RectangleF\&, const ArrayPtr\<PointF\>\&) constructeur


Construit une nouvelle instance de la classe [Matrix](../) à la transformation géométrique définie par le rectangle et le tableau de points spécifiés.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const RectangleF &rect, const ArrayPtr<PointF> &plgpts)
```

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Matrix](../)
* Classe [Rectangle](../../../system.drawing/rectangle/)
* Classe [Point](../../../system.drawing/point/)
* Classe [RectangleF](../../../system.drawing/rectanglef/)
* Classe [PointF](../../../system.drawing/pointf/)
* Espace de noms [System::Drawing::Drawing2D](../../)
* Bibliothèque [Aspose.Slides](../../../)
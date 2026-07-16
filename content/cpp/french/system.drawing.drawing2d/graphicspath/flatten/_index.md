---
title: Flatten()
second_title: Aspose.Slides pour C++ Référence API
description: Aplatisse chaque courbe du tracé en les convertissant en une série de lignes connectées. La valeur de platitude de 0.25 est utilisée.
type: docs
weight: 391
url: /fr/system.drawing.drawing2d/graphicspath/flatten/
---
## GraphicsPath::Flatten() method


Aplatisse chaque courbe du tracé en les convertissant en une série de lignes connectées. La valeur de platitude de 0.25 est utilisée.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten()
```

## GraphicsPath::Flatten(const MatrixPtr\&) method


Aplatisse chaque courbe du tracé en les convertissant en une série de lignes connectées. La valeur de platitude de 0.25 est utilisée.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | La matrice de transformation à appliquer au tracé avant l'aplatissement |

## GraphicsPath::Flatten(const MatrixPtr\&, float) method


Aplatisse chaque courbe du tracé en les convertissant en une série de lignes connectées.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix, float flatness)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | La matrice de transformation à appliquer au tracé avant l'aplatissement |
| flatness | **float** | Spécifie l'erreur maximale autorisée entre la courbe et son approximation aplatie |

## Voir aussi

* Typedef [MatrixPtr](../../matrixptr/)
* Classe [GraphicsPath](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)
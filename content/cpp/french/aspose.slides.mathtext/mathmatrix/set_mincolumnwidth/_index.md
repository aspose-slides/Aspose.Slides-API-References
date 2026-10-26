---
title: set_MinColumnWidth()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Largeur minimale de colonne en twips (1/20e de point) L'espacement de l'écart (également appelé \\u201CColumn Gap\\u201D ou \\u201CGap Width\\u201D) est ajouté à la MinColumnWidth pour déterminer l'espacement total des colonnes de la matrice (distance entre les mêmes bords de colonnes différentes). Valeur par défaut : 0."
type: docs
weight: 92
url: /fr/aspose.slides.mathtext/mathmatrix/set_mincolumnwidth/
---
## MathMatrix::set_MinColumnWidth(uint32_t) méthode

Largeur minimale de colonne en twips (1/20e de point) L'espacement de l'écart (également appelé « Column Gap » ou « Gap Width ») est ajouté à la MinColumnWidth pour déterminer le total de la matrice [Column](../../../aspose.slides/column/) Spacing (distance entre les mêmes bords de colonnes différentes). Valeur par défaut : 0.

```cpp
void Aspose::Slides::MathText::MathMatrix::set_MinColumnWidth(uint32_t value) override
```

## Remarques

Exemple :
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## Voir aussi

* Classe [MathMatrix](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)
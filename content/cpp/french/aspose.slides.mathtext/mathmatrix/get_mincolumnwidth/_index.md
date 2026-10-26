---
title: get_MinColumnWidth()
second_title: Référence API Aspose.Slides pour C++
description: "Largeur minimale de colonne en twips (1/20e d'un point) L'espacement de la marge (également appelé \\u201CColumn Gap\\u201D ou \\u201CGap Width\\u201D) est ajouté à MinColumnWidth pour déterminer l'espacement total de la matrice Column Spacing (distance entre les mêmes bords de différentes colonnes). Par défaut : 0."
type: docs
weight: 79
url: /fr/aspose.slides.mathtext/mathmatrix/get_mincolumnwidth/
---
## MathMatrix::get_MinColumnWidth() méthode


Largeur minimale de colonne en twips (1/20e d'un point) L'espacement de la marge (également appelé \\u201CColumn Gap\\u201D ou \\u201CGap Width\\u201D) est ajouté à MinColumnWidth pour déterminer le total de la matrice [Column](../../../aspose.slides/column/) Espacement (distance entre les mêmes bords de différentes colonnes). Par défaut : 0.

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_MinColumnWidth() override
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
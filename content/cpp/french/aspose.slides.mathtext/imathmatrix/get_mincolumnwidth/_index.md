---
title: get_MinColumnWidth()
second_title: Référence API Aspose.Slides pour C++
description: "Largeur minimale de colonne en twips (1/20e d'un point) L'espacement de l'écart (également appelé \\u201CColumn Gap\\u201D ou \\u201CGap Width\\u201D) est ajouté à la MinColumnWidth pour déterminer le total Matrix Column Spacing (distance entre les mêmes bords de différentes colonnes). Valeur par défaut: 0."
type: docs
weight: 79
url: /fr/aspose.slides.mathtext/imathmatrix/get_mincolumnwidth/
---
## IMathMatrix::get_MinColumnWidth() méthode

Largeur minimale de colonne en twips (1/20e d’un point) L’espacement de l’écart (également appelé «Column Gap» ou «Gap Width») est ajouté à la MinColumnWidth pour déterminer le total Matrix [Column](../../../aspose.slides/column/) Spacing (distance entre les mêmes bords de différentes colonnes). Valeur par défaut : 0.

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_MinColumnWidth()=0
```

## Remarques

Exemple :
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## Voir aussi

* classe [IMathMatrix](../)
* espace de noms [Aspose::Slides::MathText](../../)
* bibliothèque [Aspose.Slides](../../../)
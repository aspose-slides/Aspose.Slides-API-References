---
title: set_MinColumnWidth()
second_title: Référence API Aspose.Slides pour C++
description: "Largeur minimale de colonne en twips (1/20e de point) L'espacement de la gouttière (également appelé \\u201CColumn Gap\\u201D ou \\u201CGap Width\\u201D) est ajouté à la MinColumnWidth pour déterminer l'espacement total des colonnes de la Matrix (distance entre les mêmes bords de colonnes différentes). Valeur par défaut : 0."
type: docs
weight: 92
url: /fr/aspose.slides.mathtext/imathmatrix/set_mincolumnwidth/
---
## IMathMatrix::set_MinColumnWidth(uint32_t) méthode

Largeur minimale de colonne en twips (1/20e de point). L'espacement de la gouttière (également appelé «Column Gap» ou «Gap Width») est ajouté à la MinColumnWidth pour déterminer l'espacement total de la Matrix [Column](../../../aspose.slides/column/) (distance entre les mêmes bords de colonnes différentes). Valeur par défaut : 0.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_MinColumnWidth(uint32_t value)=0
```

## Remarques

Exemple : 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## Voir aussi

* Classe [IMathMatrix](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)
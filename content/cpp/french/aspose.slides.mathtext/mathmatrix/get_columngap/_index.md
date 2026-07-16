---
title: get_ColumnGap()
second_title: Référence de l'API Aspose.Slides pour C++
description: "La valeur de l'espacement horizontal entre les colonnes d'une matrice ; si le ColumnGapRule est défini à 3 (\"Exactly\"), l'unité est interprétée comme des twips (1/20e d'un point). Si le ColumnGapRule est défini à 4 (\"Multiple\"), l'unité est interprétée comme un nombre d'incréments de 0,5 em. Dans les autres cas, ignoré. Valeur par défaut : 0"
type: docs
weight: 131
url: /fr/aspose.slides.mathtext/mathmatrix/get_columngap/
---
## MathMatrix::get_ColumnGap() méthode

Valeur de l'espacement horizontal entre les colonnes d'une matrice; si le ColumnGapRule est défini sur 3 (\"Exactly\"), l'unité est interprétée comme des twips (1/20e d'un point) si le ColumnGapRule est défini sur 4 (\"Multiple\"), l'unité est interprétée comme un nombre d'incréments de 0.5 em. Dans les autres cas, ignoré. Valeur par défaut: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_ColumnGap() override
```

## Remarques

Exemple :
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## Voir aussi

* Classe [MathMatrix](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)
---
title: get_ColumnGap()
second_title: Référence API Aspose.Slides pour C++
description: "La valeur de l'espacement horizontal entre les colonnes d'une matrice ; Si le ColumnGapRule est défini sur 3 (\"Exactly\"), alors l'unité est interprétée comme des twips (1/20e d'un point) Si le ColumnGapRule est défini sur 4 (\"Multiple\"), alors l'unité est interprétée comme un nombre d'incréments de 0,5 em. Dans les autres cas, ignoré. Valeur par défaut : 0"
type: docs
weight: 131
url: /fr/aspose.slides.mathtext/imathmatrix/get_columngap/
---
## IMathMatrix::get_ColumnGap() méthode


La valeur de l'espacement horizontal entre les colonnes d'une matrice ; Si le ColumnGapRule est défini sur 3 (\"Exactly\"), alors l'unité est interprétée comme des twips (1/20e d'un point) Si le ColumnGapRule est défini sur 4 (\"Multiple\"), alors l'unité est interprétée comme un nombre d'incréments de 0.5 em. Dans les autres cas, ignoré. Valeur par défaut : 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_ColumnGap()=0
```

## Remarques


Exemple : 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## Voir aussi

* Classe [IMathMatrix](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)
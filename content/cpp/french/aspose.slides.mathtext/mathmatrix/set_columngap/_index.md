---
title: set_ColumnGap()
second_title: Référence de l'API Aspose.Slides pour C++
description: "La valeur de l'espacement horizontal entre les colonnes d'une matrice ; si le ColumnGapRule est réglé à 3 (\"Exactly\"), alors l'unité est interprétée comme des twips (1/20e d'un point). Si le ColumnGapRule est réglé à 4 (\"Multiple\"), alors l'unité est interprétée comme un nombre d'incréments de 0,5 em. Dans les autres cas, ignoré. Valeur par défaut : 0"
type: docs
weight: 144
url: /fr/aspose.slides.mathtext/mathmatrix/set_columngap/
---
## MathMatrix::set_ColumnGap(uint32_t) méthode


La valeur de l'espacement horizontal entre les colonnes d'une matrice ; si le ColumnGapRule est réglé à 3 ("Exactly"), alors l'unité est interprétée comme des twips (1/20e d'un point). Si le ColumnGapRule est réglé à 4 ("Multiple"), alors l'unité est interprétée comme un nombre d'incréments de 0,5 em. Dans les autres cas, ignoré. Valeur par défaut : 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_ColumnGap(uint32_t value) override
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
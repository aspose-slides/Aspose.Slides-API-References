---
title: set_RowGap()
second_title: Référence de l'API Aspose.Slides pour C++
description: "La valeur de l'espacement vertical entre les lignes d'une matrice ; si le RowGapRule est défini sur 3 (\"Exactly\"), alors l'unité est interprétée comme des twips (1/20e d'un point) si le RowGapRule est défini sur 4 (\"Multiple\"), alors l'unité est interprétée comme des demi-lignes. Valeur par défaut : 0"
type: docs
weight: 196
url: /fr/aspose.slides.mathtext/mathmatrix/set_rowgap/
---
## MathMatrix::set_RowGap(uint32_t) méthode

La valeur de l’espacement vertical entre les lignes d’une matrice ; si le RowGapRule est défini sur 3 ("Exactly"), alors l’unité est interprétée comme des twips (1/20e d’un point) si le RowGapRule est défini sur 4 ("Multiple"), alors l’unité est interprétée comme des demi-lignes. Valeur par défaut : 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGap(uint32_t value) override
```

## Remarques

Exemple :
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## Voir aussi

* Classe [MathMatrix](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)
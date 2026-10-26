---
title: get_RowGap()
second_title: "Référence API Aspose.Slides pour C++"
description: "La valeur de l'espacement vertical entre les lignes d'une matrice ; Si le RowGapRule est défini sur 3 (\"Exactly\"), alors l'unité est interprétée comme des twips (1/20e de point) Si le RowGapRule est défini sur 4 (\"Multiple\"), alors l'unité est interprétée comme des demi-lignes. Valeur par défaut : 0"
type: docs
weight: 183
url: /fr/aspose.slides.mathtext/imathmatrix/get_rowgap/
---
## IMathMatrix::get_RowGap() méthode

La valeur de l'espacement vertical entre les lignes d'une matrice ; Si le RowGapRule est défini sur 3 ("Exactly"), alors l'unité est interprétée comme des twips (1/20e de point) Si le RowGapRule est défini sur 4 ("Multiple"), alors l'unité est interprétée comme des demi-lignes. Valeur par défaut : 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_RowGap()=0
```

## Remarques

Exemple :
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## Voir aussi

* Classe [IMathMatrix](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)
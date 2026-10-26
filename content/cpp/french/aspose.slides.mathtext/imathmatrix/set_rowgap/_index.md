---
title: set_RowGap()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Valeur de l'espacement vertical entre les lignes d'une matrice ; Si le RowGapRule est défini sur 3 (\"Exactly\"), l'unité est interprétée comme des twips (1/20e d'un point) Si le RowGapRule est défini sur 4 (\"Multiple\"), l'unité est interprétée comme des demi-lignes. Valeur par défaut : 0"
type: docs
weight: 196
url: /fr/aspose.slides.mathtext/imathmatrix/set_rowgap/
---
## IMathMatrix::set_RowGap(uint32_t) méthode

La valeur de l'espacement vertical entre les lignes d'une matrice; Si le RowGapRule est défini sur 3 (\"Exactly\"), l'unité est interprétée comme des twips (1/20e d'un point) Si le RowGapRule est défini sur 4 (\"Multiple\"), l'unité est interprétée comme des demi-lignes. Valeur par défaut: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGap(uint32_t value)=0
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
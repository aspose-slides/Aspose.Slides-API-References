---
title: get_RowGap()
second_title: Aspose.Slides pour C++ Référence API
description: "La valeur de l'espacement vertical entre les lignes d'une matrice ; Si le RowGapRule est défini à 3 (\"Exactly\"), alors l'unité est interprétée comme des twips (1/20e d'un point) Si le RowGapRule est défini à 4 (\"Multiple\"), alors l'unité est interprétée comme des demi-lignes. Valeur par défaut : 0"
type: docs
weight: 183
url: /fr/aspose.slides.mathtext/mathmatrix/get_rowgap/
---
## MathMatrix::get_RowGap() méthode

La valeur de l'espacement vertical entre les lignes d'une matrice; Si le RowGapRule est défini à 3 ("Exactly"), alors l'unité est interprétée comme des twips (1/20eme d'un point) Si le RowGapRule est défini à 4 ("Multiple"), alors l'unité est interprétée comme des demi-lignes. Valeur par défaut : 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_RowGap() override
```
## Remarques

Exemple:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```
## Voir aussi

* Classe [MathMatrix](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)
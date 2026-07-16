---
title: get_RowGapRule()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Le type d'espacement vertical entre les lignes d'une matrice ; les unités d'espacement vertical peuvent être des lignes ou des points (stockés sous forme de twips). Valeur par défaut : SingleSpacingGap (0)"
type: docs
weight: 157
url: /fr/aspose.slides.mathtext/mathmatrix/get_rowgaprule/
---
## MathMatrix::get_RowGapRule() méthode

Le type d'espacement vertical entre les lignes d'une matrice; les unités d'espacement vertical peuvent être des lignes ou des points (stockés sous forme de twips). Valeur par défaut: SingleSpacingGap (0)

```cpp
MathSpacingRules Aspose::Slides::MathText::MathMatrix::get_RowGapRule() override
```

## Remarques

Exemple :
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Voir aussi

* Enum [MathSpacingRules](../../mathspacingrules/)
* Classe [MathMatrix](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
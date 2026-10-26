---
title: get_ColumnGapRule()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Le type d'espacement horizontal entre les colonnes d'une matrice; les unités d'espacement horizontal peuvent être des ems ou des points (stockés en twips). Valeur par défaut: SingleSpacingGap (0)"
type: docs
weight: 105
url: /fr/aspose.slides.mathtext/mathmatrix/get_columngaprule/
---
## MathMatrix::get_ColumnGapRule() méthode


Le type d'espacement horizontal entre les colonnes d'une matrice; les unités d'espacement horizontal peuvent être des ems ou des points (stockés en twips). Valeur par défaut: SingleSpacingGap (0)

```cpp
MathSpacingRules Aspose::Slides::MathText::MathMatrix::get_ColumnGapRule() override
```

## Remarques


Exemple:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Voir aussi

* Enum [MathSpacingRules](../../mathspacingrules/)
* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
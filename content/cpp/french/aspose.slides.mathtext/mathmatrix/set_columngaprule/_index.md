---
title: set_ColumnGapRule()
second_title: Référence API Aspose.Slides pour C++
description: "Le type d'espacement horizontal entre les colonnes d'une matrice ; les unités d'espacement horizontal peuvent être des ems ou des points (stockés en twips). Par défaut : SingleSpacingGap (0)"
type: docs
weight: 118
url: /fr/aspose.slides.mathtext/mathmatrix/set_columngaprule/
---
## MathMatrix::set_ColumnGapRule(MathSpacingRules) méthode


Le type d'espacement horizontal entre les colonnes d'une matrice ; les unités d'espacement horizontal peuvent être des ems ou des points (stockés en twips). Par défaut : SingleSpacingGap (0)

```cpp
void Aspose::Slides::MathText::MathMatrix::set_ColumnGapRule(MathSpacingRules value) override
```

## Remarques


Exemple: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Voir aussi

* Enum [MathSpacingRules](../../mathspacingrules/)
* Classe [MathMatrix](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
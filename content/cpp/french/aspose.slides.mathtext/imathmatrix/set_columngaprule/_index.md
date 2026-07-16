---
title: set_ColumnGapRule()
second_title: Référence API Aspose.Slides pour C++
description: "Le type d'espacement horizontal entre les colonnes d'une matrice; les unités d'espacement horizontal peuvent être des ems ou des points (stockés en twips). Valeur par défaut: SingleSpacingGap (0)"
type: docs
weight: 118
url: /fr/aspose.slides.mathtext/imathmatrix/set_columngaprule/
---
## IMathMatrix::set_ColumnGapRule(MathSpacingRules) méthode

Le type d'espacement horizontal entre les colonnes d'une matrice ; les unités d'espacement horizontal peuvent être des ems ou des points (stockés en twips). Valeur par défaut : SingleSpacingGap (0)

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_ColumnGapRule(MathSpacingRules value)=0
```

## Remarques

Exemple:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Voir aussi

* Enum [MathSpacingRules](../../mathspacingrules/)
* Classe [IMathMatrix](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)
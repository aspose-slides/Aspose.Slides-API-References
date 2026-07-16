---
title: set_RowGapRule()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Le type d'espacement vertical entre les lignes d'une matrice; les unités d'espacement vertical peuvent être des lignes ou des points (stockés en twips). Par défaut: SingleSpacingGap (0)"
type: docs
weight: 170
url: /fr/aspose.slides.mathtext/imathmatrix/set_rowgaprule/
---
## IMathMatrix::set_RowGapRule(MathSpacingRules) méthode

Le type d'espacement vertical entre les lignes d'une matrice ; les unités d'espacement vertical peuvent être des lignes ou des points (stockés en twips). Par défaut: SingleSpacingGap (0)

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGapRule(MathSpacingRules value)=0
```

## Remarques

Exemple:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Voir aussi

* Énum [MathSpacingRules](../../mathspacingrules/)
* Classe [IMathMatrix](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)
---
title: get_RowSpacingRule()
second_title: Référence API Aspose.Slides pour C++
description: Le type d'espacement vertical entre les éléments du tableau
type: docs
weight: 92
url: /fr/aspose.slides.mathtext/imatharray/get_rowspacingrule/
---
## IMathArray::get_RowSpacingRule() méthode

Le type d'espacement vertical entre les éléments du tableau

```cpp
virtual MathRowSpacingRule Aspose::Slides::MathText::IMathArray::get_RowSpacingRule()=0
```

## Remarques

Exemple :
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::OneAndAHalfLineGap);
```

## Voir aussi

* Enum [MathRowSpacingRule](../../mathrowspacingrule/)
* Classe [IMathArray](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)
---
title: set_GrowToMatchOperandHeight()
second_title: Référence de l'API Aspose.Slides pour C++
description: Le caractère de l'opérateur s'étend verticalement pour correspondre à la hauteur de son opérande
type: docs
weight: 105
url: /fr/aspose.slides.mathtext/mathnaryoperator/set_growtomatchoperandheight/
---
## MathNaryOperator::set_GrowToMatchOperandHeight(bool) méthode


Le caractère de l'opérateur s'étend verticalement pour correspondre à la hauteur de son opérande

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_GrowToMatchOperandHeight(bool value) override
```

## Remarques


Exemple :
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## Voir aussi

* Classe [MathNaryOperator](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)
---
title: get_GrowToMatchOperandHeight()
second_title: Référence API Aspose.Slides pour C++
description: Le caractère opérateur grandit verticalement pour correspondre à la hauteur de son opérande
type: docs
weight: 92
url: /fr/aspose.slides.mathtext/mathnaryoperator/get_growtomatchoperandheight/
---
## MathNaryOperator::get_GrowToMatchOperandHeight() méthode

Le caractère opérateur grandit verticalement pour correspondre à la hauteur de son opérande

```cpp
bool Aspose::Slides::MathText::MathNaryOperator::get_GrowToMatchOperandHeight() override
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
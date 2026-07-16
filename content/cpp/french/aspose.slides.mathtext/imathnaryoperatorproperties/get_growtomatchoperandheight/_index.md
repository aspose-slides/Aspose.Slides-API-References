---
title: get_GrowToMatchOperandHeight()
second_title: Référence API Aspose.Slides pour C++
description: Le caractère de l'opérateur croît verticalement pour correspondre à la hauteur de son opérande
type: docs
weight: 53
url: /fr/aspose.slides.mathtext/imathnaryoperatorproperties/get_growtomatchoperandheight/
---
## IMathNaryOperatorProperties::get_GrowToMatchOperandHeight() méthode

Le caractère de l'opérateur croît verticalement pour correspondre à la hauteur de son opérande

```cpp
virtual bool Aspose::Slides::MathText::IMathNaryOperatorProperties::get_GrowToMatchOperandHeight()=0
```

## Remarques

Exemple:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## Voir aussi

* Classe [IMathNaryOperatorProperties](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)
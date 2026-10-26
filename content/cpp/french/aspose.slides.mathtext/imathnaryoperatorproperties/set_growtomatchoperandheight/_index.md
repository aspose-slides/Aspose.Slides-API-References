---
title: set_GrowToMatchOperandHeight()
second_title: Référence de l'API Aspose.Slides pour C++
description: Le caractère d'opérateur s'étend verticalement pour correspondre à la hauteur de son opérande
type: docs
weight: 66
url: /fr/aspose.slides.mathtext/imathnaryoperatorproperties/set_growtomatchoperandheight/
---
## IMathNaryOperatorProperties::set_GrowToMatchOperandHeight(bool) méthode

Le caractère d’opérateur s’étend verticalement pour correspondre à la hauteur de son opérande

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_GrowToMatchOperandHeight(bool value)=0
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
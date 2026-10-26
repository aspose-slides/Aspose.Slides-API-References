---
title: get_LimitLocation()
second_title: Référence de l'API Aspose.Slides for C++
description: L'emplacement des limites (indice et exposant)
type: docs
weight: 66
url: /fr/aspose.slides.mathtext/mathnaryoperator/get_limitlocation/
---
## MathNaryOperator::get_LimitLocation() méthode

L'emplacement des limites (indice et exposant)

```cpp
MathLimitLocations Aspose::Slides::MathText::MathNaryOperator::get_LimitLocation() override
```

## Remarques

Exemple:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Voir aussi

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Classe [MathNaryOperator](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
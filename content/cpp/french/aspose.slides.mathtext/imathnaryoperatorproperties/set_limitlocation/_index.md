---
title: set_LimitLocation()
second_title: Référence API Aspose.Slides pour C++
description: L'emplacement des limites (indice et exposant)
type: docs
weight: 40
url: /fr/aspose.slides.mathtext/imathnaryoperatorproperties/set_limitlocation/
---
## IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations) méthode

L'emplacement des limites (indice et exposant)

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations value)=0
```

## Remarques

Exemple :

```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Voir aussi

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Classe [IMathNaryOperatorProperties](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)
---
title: get_LimitLocation()
second_title: Référence API Aspose.Slides pour C++
description: L'emplacement des limites (indice et exposant)
type: docs
weight: 27
url: /fr/aspose.slides.mathtext/imathnaryoperatorproperties/get_limitlocation/
---
## IMathNaryOperatorProperties::get_LimitLocation() méthode


L'emplacement des limites (indice et exposant)

```cpp
virtual MathLimitLocations Aspose::Slides::MathText::IMathNaryOperatorProperties::get_LimitLocation()=0
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
* Library [Aspose.Slides](../../../)
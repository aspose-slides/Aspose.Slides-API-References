---
title: set_LimitLocation()
second_title: "Référence de l'API Aspose.Slides pour C++"
description: "L'emplacement des limites (indice et exposant)"
type: docs
weight: 79
url: /fr/aspose.slides.mathtext/mathnaryoperator/set_limitlocation/
---
## MathNaryOperator::set_LimitLocation(MathLimitLocations) méthode


L'emplacement des limites (indice et exposant)

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_LimitLocation(MathLimitLocations value) override
```

## Remarques


Exemple :
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Voir aussi

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Classe [MathNaryOperator](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)
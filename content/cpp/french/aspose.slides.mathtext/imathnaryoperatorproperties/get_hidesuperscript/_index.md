---
title: get_HideSuperscript()
second_title: Référence de l'API Aspose.Slides pour C++
description: Masquer l'exposant
type: docs
weight: 105
url: /fr/aspose.slides.mathtext/imathnaryoperatorproperties/get_hidesuperscript/
---
## IMathNaryOperatorProperties::get_HideSuperscript() méthode


Masquer l'exposant

```cpp
virtual bool Aspose::Slides::MathText::IMathNaryOperatorProperties::get_HideSuperscript()=0
```

## Remarques


Exemple: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSuperscript(true);
```

## Voir aussi

* Classe [IMathNaryOperatorProperties](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)
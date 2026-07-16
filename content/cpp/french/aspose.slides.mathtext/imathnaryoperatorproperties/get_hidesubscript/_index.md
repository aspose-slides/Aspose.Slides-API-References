---
title: get_HideSubscript()
second_title: Référence de l'API Aspose.Slides pour C++
description: Masquer le sous-script
type: docs
weight: 79
url: /fr/aspose.slides.mathtext/imathnaryoperatorproperties/get_hidesubscript/
---
## IMathNaryOperatorProperties::get_HideSubscript() méthode

Masquer le sous-script

```cpp
virtual bool Aspose::Slides::MathText::IMathNaryOperatorProperties::get_HideSubscript()=0
```

## Remarques

Exemple:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSubscript(true);
```

## Voir aussi

* Classe [IMathNaryOperatorProperties](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)
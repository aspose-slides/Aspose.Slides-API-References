---
title: get_HideSubscript()
second_title: Référence de l'API Aspose.Slides pour C++
description: Masquer le sous-script
type: docs
weight: 118
url: /fr/aspose.slides.mathtext/mathnaryoperator/get_hidesubscript/
---
## MathNaryOperator::get_HideSubscript() méthode

Masquer le sous-script

```cpp
bool Aspose::Slides::MathText::MathNaryOperator::get_HideSubscript() override
```

## Remarques

Exemple :
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSubscript(true);
```

## Voir aussi

* Classe [MathNaryOperator](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)
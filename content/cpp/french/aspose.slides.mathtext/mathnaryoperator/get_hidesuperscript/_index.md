---
title: get_HideSuperscript()
second_title: Référence de l'API Aspose.Slides pour C++
description: Masquer le superscript
type: docs
weight: 144
url: /fr/aspose.slides.mathtext/mathnaryoperator/get_hidesuperscript/
---
## MathNaryOperator::get_HideSuperscript() méthode


Masquer le superscript

```cpp
bool Aspose::Slides::MathText::MathNaryOperator::get_HideSuperscript() override
```

## Remarques


Exemple:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSuperscript(true);
```

## Voir aussi

* Classe [MathNaryOperator](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)
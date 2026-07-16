---
title: get_Superscript()
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie un argument de exposant qui, par exemple, dans le cas d'une intégrale, définit la limite supérieure
type: docs
weight: 27
url: /fr/aspose.slides.mathtext/mathnaryoperator/get_superscript/
---
## MathNaryOperator::get_Superscript() méthode


Spécifie un argument de exposant qui, par exemple, dans le cas d'une intégrale, définit la limite supérieure

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Superscript() override
```

## Remarques


Exemple :
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto superscriptArg = naryOperator->get_Superscript();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathNaryOperator](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)
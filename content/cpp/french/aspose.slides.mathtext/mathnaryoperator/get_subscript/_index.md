---
title: get_Subscript()
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie un argument de sous-script qui, par exemple, dans le cas d'une intégrale, définit la limite inférieure
type: docs
weight: 14
url: /fr/aspose.slides.mathtext/mathnaryoperator/get_subscript/
---
## MathNaryOperator::get_Subscript() method


Spécifie un argument de sous-script qui, par exemple, dans le cas d’une intégrale, définit la limite inférieure

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Subscript() override
```

## Remarques


Exemple:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto subscriptArg = naryOperator->get_Subscript();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathNaryOperator](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)
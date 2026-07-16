---
title: get_Subscript()
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie un argument indice qui, par exemple, dans le cas d'un entier, définit la limite inférieure
type: docs
weight: 14
url: /fr/aspose.slides.mathtext/imathnaryoperator/get_subscript/
---
## IMathNaryOperator::get_Subscript() méthode

Spécifie un argument indice qui, par exemple, dans le cas d'un entier, définit la limite inférieure

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Subscript()=0
```

## Remarques

Exemple :
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto subscriptArg = naryOperator->get_Subscript();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathNaryOperator](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)
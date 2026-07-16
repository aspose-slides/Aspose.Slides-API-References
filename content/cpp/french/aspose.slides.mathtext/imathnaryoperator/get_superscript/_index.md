---
title: get_Superscript()
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie un argument de exposant qui, par exemple, dans le cas d'une intégrale, définit la borne supérieure
type: docs
weight: 27
url: /fr/aspose.slides.mathtext/imathnaryoperator/get_superscript/
---
## IMathNaryOperator::get_Superscript() méthode

Spécifie un argument de exposant qui, par exemple, dans le cas d'une intégrale, définit la borne supérieure

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Superscript()=0
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
* Classe [IMathNaryOperator](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
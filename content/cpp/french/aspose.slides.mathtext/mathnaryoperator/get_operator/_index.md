---
title: get_Operator()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Caractère d'opérateur N-aire Par exemple: '\\u2211', '\\u222B'"
type: docs
weight: 40
url: /fr/aspose.slides.mathtext/mathnaryoperator/get_operator/
---
## MathNaryOperator::get_Operator() méthode

Caractère d'opérateur N-aire Par exemple: '\\u2211', '\\u222B'

```cpp
char16_t Aspose::Slides::MathText::MathNaryOperator::get_Operator() override
```

## Remarques

Exemple:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Voir aussi

* Classe [MathNaryOperator](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)
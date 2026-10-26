---
title: set_Operator()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Caractère d'opérateur Nary Par exemple : '\\u2211', '\\u222B'"
type: docs
weight: 53
url: /fr/aspose.slides.mathtext/mathnaryoperator/set_operator/
---
## MathNaryOperator::set_Operator(char16_t) méthode


Caractère de l'opérateur Nary Par exemple : '\\u2211', '\\u222B'

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_Operator(char16_t value) override
```

## Remarques


Exemple : 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Voir aussi

* Classe [MathNaryOperator](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)
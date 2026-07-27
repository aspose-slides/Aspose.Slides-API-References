---
title: get_RowSpacingRule()
second_title: Referência da API Aspose.Slides para C++
description: O tipo de espaçamento vertical entre os elementos da matriz
type: docs
weight: 92
url: /pt/aspose.slides.mathtext/imatharray/get_rowspacingrule/
---
## IMathArray::get_RowSpacingRule() método

O tipo de espaçamento vertical entre os elementos da matriz

```cpp
virtual MathRowSpacingRule Aspose::Slides::MathText::IMathArray::get_RowSpacingRule()=0
```

## Observações

Exemplo:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::OneAndAHalfLineGap);
```

## Ver Também

* Enum [MathRowSpacingRule](../../mathrowspacingrule/)
* Classe [IMathArray](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)
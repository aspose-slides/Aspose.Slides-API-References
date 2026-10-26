---
title: get_RowSpacingRule()
second_title: Aspose.Slides per C++ Riferimento API
description: Il tipo di spaziatura verticale tra gli elementi dell'array
type: docs
weight: 92
url: /it/aspose.slides.mathtext/imatharray/get_rowspacingrule/
---
## IMathArray::get_RowSpacingRule() metodo

Il tipo di spaziatura verticale tra gli elementi dell'array

```cpp
virtual MathRowSpacingRule Aspose::Slides::MathText::IMathArray::get_RowSpacingRule()=0
```

## Osservazioni

Esempio:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::OneAndAHalfLineGap);
```

## Vedi anche

* Enum [MathRowSpacingRule](../../mathrowspacingrule/)
* Classe [IMathArray](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)
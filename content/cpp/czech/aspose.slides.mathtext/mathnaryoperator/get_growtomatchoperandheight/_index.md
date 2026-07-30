---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides pro C++ API Reference
description: Znak operátoru roste svisle, aby odpovídal výšce operandu
type: docs
weight: 92
url: /cs/aspose.slides.mathtext/mathnaryoperator/get_growtomatchoperandheight/
---
## MathNaryOperator::get_GrowToMatchOperandHeight() metoda


Znak operátoru roste svisle, aby odpovídal výšce operandu

```cpp
bool Aspose::Slides::MathText::MathNaryOperator::get_GrowToMatchOperandHeight() override
```

## Poznámky


Příklad: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## Viz také

* třída [MathNaryOperator](../)
* jmenný prostor [Aspose::Slides::MathText](../../)
* knihovna [Aspose.Slides](../../../)
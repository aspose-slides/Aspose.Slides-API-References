---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides pro C++ API Reference
description: Znak operátoru roste vertikálně, aby odpovídal výšce jeho operandu
type: docs
weight: 105
url: /cs/aspose.slides.mathtext/mathnaryoperator/set_growtomatchoperandheight/
---
## MathNaryOperator::set_GrowToMatchOperandHeight(bool) metoda


Znak operátoru roste vertikálně, aby odpovídal výšce jeho operandu

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_GrowToMatchOperandHeight(bool value) override
```

## Poznámky


Příklad: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## Viz také

* Třída [MathNaryOperator](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)
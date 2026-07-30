---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Operátorový znak roste vertikálně, aby odpovídal výšce operandu
type: docs
weight: 66
url: /cs/aspose.slides.mathtext/imathnaryoperatorproperties/set_growtomatchoperandheight/
---
## IMathNaryOperatorProperties::set_GrowToMatchOperandHeight(bool) metoda


Operátorový znak roste vertikálně, aby odpovídal výšce jeho operandů

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_GrowToMatchOperandHeight(bool value)=0
```

## Poznámky


Příklad: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## Viz také

* Třída [IMathNaryOperatorProperties](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)
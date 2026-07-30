---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Operátor Character roste svisle tak, aby odpovídal výšce svého operandu
type: docs
weight: 53
url: /cs/aspose.slides.mathtext/imathnaryoperatorproperties/get_growtomatchoperandheight/
---
## IMathNaryOperatorProperties::get_GrowToMatchOperandHeight() metoda


Operator Character roste svisle tak, aby odpovídal výšce jeho operandu

```cpp
virtual bool Aspose::Slides::MathText::IMathNaryOperatorProperties::get_GrowToMatchOperandHeight()=0
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
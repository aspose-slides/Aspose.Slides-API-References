---
title: set_HideSubscript()
second_title: Aspose.Slides pro C++ API Reference
description: Skrýt dolní index
type: docs
weight: 131
url: /cs/aspose.slides.mathtext/mathnaryoperator/set_hidesubscript/
---
## MathNaryOperator::set_HideSubscript(bool) metoda


Skrýt dolní index

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_HideSubscript(bool value) override
```

## Poznámky


Příklad: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSubscript(true);
```

## Viz také

* Třída [MathNaryOperator](../)
* Obor názvů [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)
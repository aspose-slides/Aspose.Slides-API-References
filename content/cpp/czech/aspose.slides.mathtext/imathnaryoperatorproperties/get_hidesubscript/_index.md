---
title: get_HideSubscript()
second_title: Aspose.Slides pro C++ API Reference
description: Skrýt dolní index
type: docs
weight: 79
url: /cs/aspose.slides.mathtext/imathnaryoperatorproperties/get_hidesubscript/
---
## IMathNaryOperatorProperties::get_HideSubscript() metoda


Skrýt dolní index

```cpp
virtual bool Aspose::Slides::MathText::IMathNaryOperatorProperties::get_HideSubscript()=0
```

## Poznámky


Příklad:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSubscript(true);
```

## Viz také

* Třída [IMathNaryOperatorProperties](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)
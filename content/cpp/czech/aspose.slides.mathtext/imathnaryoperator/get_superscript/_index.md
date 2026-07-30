---
title: get_Superscript()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Určuje argument superscript, který například v případě integrálu nastavuje horní mez
type: docs
weight: 27
url: /cs/aspose.slides.mathtext/imathnaryoperator/get_superscript/
---
## IMathNaryOperator::get_Superscript() metoda

Určuje argument superscript, který například v případě integrálu nastavuje horní mez

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Superscript()=0
```

## Poznámky

Příklad:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto superscriptArg = naryOperator->get_Superscript();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [IMathNaryOperator](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)
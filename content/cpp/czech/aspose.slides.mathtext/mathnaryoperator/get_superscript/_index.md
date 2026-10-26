---
title: get_Superscript()
second_title: Aspose.Slides pro C++ referenci API
description: Určuje argument superskriptu, který například v případě integrálu nastaví horní mez
type: docs
weight: 27
url: /cs/aspose.slides.mathtext/mathnaryoperator/get_superscript/
---
## MathNaryOperator::get_Superscript() metoda


Určuje argument superskriptu, který například v případě integrálu nastaví horní mez

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Superscript() override
```

## Poznámky


Příklad: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto superscriptArg = naryOperator->get_Superscript();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [IMathElement](../../imathelement/)
* třída [MathNaryOperator](../)
* jmenný prostor [Aspose::Slides::MathText](../../)
* knihovna [Aspose.Slides](../../../)
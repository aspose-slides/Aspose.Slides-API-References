---
title: get_Superscript()
second_title: Aspose.Slides för C++ API-referens
description: Anger ett superskript-argument som till exempel i fallet med en integral sätter den övre gränsen
type: docs
weight: 27
url: /sv/aspose.slides.mathtext/mathnaryoperator/get_superscript/
---
## MathNaryOperator::get_Superscript() metod

Anger ett superskript-argument som till exempel i fallet med en integral sätter den övre gränsen

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Superscript() override
```

## Anmärkningar

Exempel:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto superscriptArg = naryOperator->get_Superscript();
```

## Se också

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathNaryOperator](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)
---
title: get_Superscript()
second_title: Aspose.Slides för C++ API-referens
description: Anger ett superskriptargument som till exempel i fallet med ett integral sätter den övre gränsen
type: docs
weight: 27
url: /sv/aspose.slides.mathtext/imathnaryoperator/get_superscript/
---
## IMathNaryOperator::get_Superscript() metod

Anger ett superskriptargument som till exempel i fallet med ett integral sätter den övre gränsen

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Superscript()=0
```

## Anmärkningar

Exempel: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto superscriptArg = naryOperator->get_Superscript();
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [IMathNaryOperator](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)
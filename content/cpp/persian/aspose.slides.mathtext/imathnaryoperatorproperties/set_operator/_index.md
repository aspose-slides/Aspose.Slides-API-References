---
title: set_Operator()
second_title: مرجع API Aspose.Slides برای C++
description: "کاراکتر عملگر Nary برای مثال: '\\u2211', '\\u222B'"
type: docs
weight: 14
url: /fa/aspose.slides.mathtext/imathnaryoperatorproperties/set_operator/
---
## IMathNaryOperatorProperties::set_Operator(char16_t) متد

کاراکتر عملگر Nary برای مثال: '\\u2211', '\\u222B'

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_Operator(char16_t value)=0
```

## توضیحات

مثال:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## مراجع

* کلاس [IMathNaryOperatorProperties](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
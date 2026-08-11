---
title: set_Operator()
second_title: مرجع API Aspose.Slides برای C++
description: "کاراکتر عملگر Nary برای مثال: '\\u2211', '\\u222B'"
type: docs
weight: 53
url: /fa/aspose.slides.mathtext/mathnaryoperator/set_operator/
---
## MathNaryOperator::set_Operator(char16_t) متد

کاراکتر عملگر Nary برای مثال: '\\u2211', '\\u222B'

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_Operator(char16_t value) override
```

## توضیحات

مثال:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## موارد مرتبط

* کلاس [MathNaryOperator](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
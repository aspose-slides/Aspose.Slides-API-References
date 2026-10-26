---
title: get_Operator()
second_title: Aspose.Slides برای مرجع API C++
description: "کاراکتر عملگر Nary برای مثال: '\\u2211', '\\u222B'"
type: docs
weight: 40
url: /fa/aspose.slides.mathtext/mathnaryoperator/get_operator/
---
## MathNaryOperator::get_Operator() متد

کاراکتر عملگر Nary به عنوان مثال: '\\u2211', '\\u222B'

```cpp
char16_t Aspose::Slides::MathText::MathNaryOperator::get_Operator() override
```

## توضیحات

مثال:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## موارد مرتبط

* کلاس [MathNaryOperator](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
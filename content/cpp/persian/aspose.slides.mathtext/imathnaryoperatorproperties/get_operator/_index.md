---
title: get_Operator()
second_title: Aspose.Slides برای C++ مرجع API
description: "کاراکتر عملگر Nary به عنوان مثال: '\\u2211', '\\u222B'"
type: docs
weight: 1
url: /fa/aspose.slides.mathtext/imathnaryoperatorproperties/get_operator/
---
## IMathNaryOperatorProperties::get_Operator() متد

کاراکتر عملگر Nary به عنوان مثال: '\\u2211', '\\u222B'

```cpp
virtual char16_t Aspose::Slides::MathText::IMathNaryOperatorProperties::get_Operator()=0
```

## توضیحات


مثال: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## موارد مرتبط

* کلاس [IMathNaryOperatorProperties](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
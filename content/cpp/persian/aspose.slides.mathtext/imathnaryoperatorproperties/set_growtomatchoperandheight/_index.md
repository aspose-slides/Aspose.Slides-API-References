---
title: set_GrowToMatchOperandHeight()
second_title: مرجع API Aspose.Slides برای C++
description: کاراکتر عملگر به‌صورت عمودی رشد می‌کند تا با ارتفاع عملوند مطابقت داشته باشد
type: docs
weight: 66
url: /fa/aspose.slides.mathtext/imathnaryoperatorproperties/set_growtomatchoperandheight/
---
## IMathNaryOperatorProperties::set_GrowToMatchOperandHeight(bool) متد


کاراکتر عملگر به‌صورت عمودی رشد می‌کند تا با ارتفاع عملوند آن مطابقت داشته باشد

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_GrowToMatchOperandHeight(bool value)=0
```

## توضیحات


مثال: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## موارد مرتبط

* کلاس [IMathNaryOperatorProperties](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
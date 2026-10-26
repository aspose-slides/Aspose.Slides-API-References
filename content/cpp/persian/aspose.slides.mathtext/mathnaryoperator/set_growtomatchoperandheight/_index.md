---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides برای C++ مرجع API
description: کاراکتر اپراتور به صورت عمودی رشد می‌کند تا ارتفاع عملوند خود را تطبیق دهد
type: docs
weight: 105
url: /fa/aspose.slides.mathtext/mathnaryoperator/set_growtomatchoperandheight/
---
## MathNaryOperator::set_GrowToMatchOperandHeight(bool) متد

Operator Character grows vertically to match its operand height

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_GrowToMatchOperandHeight(bool value) override
```

## توضیحات

مثال:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## موارد مرتبط

* کلاس [MathNaryOperator](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
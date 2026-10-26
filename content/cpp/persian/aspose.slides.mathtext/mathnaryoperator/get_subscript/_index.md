---
title: get_Subscript()
second_title: مرجع API Aspose.Slides برای C++
description: یک آرگومان زیرنویس را مشخص می‌کند که برای مثال در مورد یک انتگرال، حد پایین را تنظیم می‌کند
type: docs
weight: 14
url: /fa/aspose.slides.mathtext/mathnaryoperator/get_subscript/
---
## MathNaryOperator::get_Subscript() متد

یک آرگومان زیرنویس را مشخص می‌کند که برای مثال در مورد یک انتگرال، حد پایین را تنظیم می‌کند

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Subscript() override
```

## توضیحات

مثال: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto subscriptArg = naryOperator->get_Subscript();
```

## مراجع دیگر

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathNaryOperator](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
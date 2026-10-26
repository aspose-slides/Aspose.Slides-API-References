---
title: get_Subscript()
second_title: Aspose.Slides برای C++ مرجع API
description: آرگومان زیرنویسی را مشخص می‌کند که به عنوان مثال در مورد یک عدد صحیح، حد پایین را تنظیم می‌نماید
type: docs
weight: 14
url: /fa/aspose.slides.mathtext/imathnaryoperator/get_subscript/
---
## IMathNaryOperator::get_Subscript() متد

یک آرگومان زیرنویس را مشخص می‌کند که به عنوان مثال در مورد یک عدد صحیح، حد پایین را تنظیم می‌نماید

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Subscript()=0
```

## توضیحات

مثال:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto subscriptArg = naryOperator->get_Subscript();
```

## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [IMathNaryOperator](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
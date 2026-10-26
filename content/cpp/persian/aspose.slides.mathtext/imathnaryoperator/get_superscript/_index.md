---
title: get_Superscript()
second_title: Aspose.Slides برای C++ مرجع API
description: آرگومان بالانویس را مشخص می‌کند که به عنوان مثال در مورد یک انتگرال، حد بالایی را تعیین می‌سازد
type: docs
weight: 27
url: /fa/aspose.slides.mathtext/imathnaryoperator/get_superscript/
---
## IMathNaryOperator::get_Superscript() متد

یک آرگومان بالانویس را مشخص می‌کند که به عنوان مثال در مورد یک انتگرال، حد بالایی را تعیین می‌سازد

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Superscript()=0
```

## توضیحات


مثال: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto superscriptArg = naryOperator->get_Superscript();
```

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [IMathNaryOperator](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
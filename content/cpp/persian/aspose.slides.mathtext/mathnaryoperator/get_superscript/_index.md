---
title: get_Superscript()
second_title: Aspose.Slides برای C++ مرجع API
description: یک آرگومان بالانویس را مشخص می‌کند که، به عنوان مثال، در مورد یک انتگرال، حد بالایی را تعیین می‌کند
type: docs
weight: 27
url: /fa/aspose.slides.mathtext/mathnaryoperator/get_superscript/
---
## MathNaryOperator::get_Superscript() متد

یک آرگومان بالانویس را مشخص می‌کند که، به‌عنوان مثال، در مورد یک انتگرال، حد بالایی را تعیین می‌کند

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Superscript() override
```

## نکات

مثال:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto superscriptArg = naryOperator->get_Superscript();
```

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathNaryOperator](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
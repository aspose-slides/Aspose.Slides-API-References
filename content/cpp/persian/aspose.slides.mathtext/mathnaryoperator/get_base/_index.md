---
title: get_Base()
second_title: مرجع API Aspose.Slides برای C++
description: آرگومان Base
type: docs
weight: 1
url: /fa/aspose.slides.mathtext/mathnaryoperator/get_base/
---
## MathNaryOperator::get_Base() متد


آرگومان Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Base() override
```

## توضیحات


مثال: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto baseArg = naryOperator->get_Base();
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathNaryOperator](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
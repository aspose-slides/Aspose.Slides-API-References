---
title: ToMathArray()
second_title: Aspose.Slides برای مرجع API C++
description: در یک آرایه عمودی قرار می‌دهد
type: docs
weight: 170
url: /fa/aspose.slides.mathtext/mathelementbase/tomatharray/
---
## MathElementBase::ToMathArray() متد

در یک آرایه عمودی قرار می‌دهد

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathElementBase::ToMathArray() override
```

### مقدار بازگشتی

New instance of type [IMathArray](../../imatharray/)
## توضیحات



مثال:
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## موارد مرتبط

* نوع تعریف [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathArray](../../imatharray/)
* کلاس [MathElementBase](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
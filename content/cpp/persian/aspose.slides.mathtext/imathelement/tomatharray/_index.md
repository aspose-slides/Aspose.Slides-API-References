---
title: ToMathArray()
second_title: مرجع API Aspose.Slides برای C++
description: در یک آرایه عمودی قرار می‌دهد
type: docs
weight: 183
url: /fa/aspose.slides.mathtext/imathelement/tomatharray/
---
## IMathElement::ToMathArray() متد


در یک آرایه عمودی قرار می‌دهد

```cpp
virtual System::SharedPtr<IMathArray> Aspose::Slides::MathText::IMathElement::ToMathArray()=0
```


### مقدار بازگشت

نمونهٔ جدید از نوع [IMathArray](../../imatharray/)
## توضیحات



مثال: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathArray](../../imatharray/)
* کلاس [IMathElement](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
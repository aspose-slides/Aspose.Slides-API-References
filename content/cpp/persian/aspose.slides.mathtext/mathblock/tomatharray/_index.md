---
title: ToMathArray()
second_title: مرجع API Aspose.Slides برای C++
description: عناصر فرزند را در یک آرایه عمودی قرار می‌دهد
type: docs
weight: 235
url: /fa/aspose.slides.mathtext/mathblock/tomatharray/
---
## MathBlock::ToMathArray() متد


عناصر فرزند را در یک آرایه عمودی قرار می‌دهد

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathBlock::ToMathArray() override
```


### مقدار بازگشت

نمونه جدیدی از نوع [IMathArray](../../imatharray/)
## توضیحات



مثال: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathArray](../../imatharray/)
* کلاس [MathBlock](../)
* فضای نام [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
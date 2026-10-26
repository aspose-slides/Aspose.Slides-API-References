---
title: MathRadical()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمونه جدید از کلاس MathRadical را مقداردهی اولیه می‌کند.
type: docs
weight: 53
url: /fa/aspose.slides.mathtext/mathradical/mathradical/
---
## MathRadical::MathRadical(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) سازنده


یک نمونه جدید از کلاس [MathRadical](../) را مقداردهی اولیه می‌کند.

```cpp
Aspose::Slides::MathText::MathRadical::MathRadical(System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> degreeArgument)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | پایه |
| degreeArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | مرتبه |
## توضیحات



مثال: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
```

## مشاهده نیز

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathRadical](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
---
title: get_Degree()
second_title: مرجع API Aspose.Slides برای C++
description: آرگومان Degree
type: docs
weight: 14
url: /fa/aspose.slides.mathtext/imathradical/get_degree/
---
## IMathRadical::get_Degree() متد


آرگومان Degree

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Degree()=0
```

## توضیحات


مثال: 
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // ریشهٔ مکعب
auto degreeElem = radical->get_Degree();
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [IMathRadical](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
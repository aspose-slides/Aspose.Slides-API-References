---
title: get_Degree()
second_title: Aspose.Slides برای مرجع API C++
description: آرگومان درجه
type: docs
weight: 14
url: /fa/aspose.slides.mathtext/mathradical/get_degree/
---
## MathRadical::get_Degree() متد


آرگومان درجه

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Degree() override
```

## توضیحات


مثال:
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto degreeElem = radical->get_Degree();
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathRadical](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
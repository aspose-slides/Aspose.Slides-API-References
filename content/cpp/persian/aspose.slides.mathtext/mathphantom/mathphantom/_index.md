---
title: MathPhantom()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمونهٔ جدید از کلاس MathPhantom را با استفاده از عنصر ریاضی پایهٔ مشخص‌شده مقداردهی اولیه می‌کند.
type: docs
weight: 144
url: /fa/aspose.slides.mathtext/mathphantom/mathphantom/
---
## MathPhantom::MathPhantom(System::SharedPtr\<IMathElement\>) سازنده

یک نمونهٔ جدید از کلاس [MathPhantom](../) را با استفاده از عنصر ریاضی پایهٔ مشخص‌شده مقداردهی اولیه می‌کند.

```cpp
Aspose::Slides::MathText::MathPhantom::MathPhantom(System::SharedPtr<IMathElement> element)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | [IMathElement](../../imathelement/) پایه‌ای که قابلیت نمایش و چیدمان آن توسط فانتوم کنترل می‌شود. این عنصر محتوا را تعریف می‌کند که ممکن است مخفی یا نمایان شود، در حالی که همچنان بر هم‌راستایی هندسی ریاضیات اطراف تأثیر می‌گذارد. |

## یادداشت‌ها

عنصر فانتوم برای رزرو یا سرکوب فضای بصری عبارت پایهٔ خود استفاده می‌شود بدون اینکه لزوماً نمایش داده شود. این عنصر با عنصر OMML **<m:phant>** مطابقت دارد.

مثال:
```cpp
System::SharedPtr<IMathElement> fraction = System::MakeObject<MathFraction>(
    System::MakeObject<MathematicalText>(u"1"),
    System::MakeObject<MathematicalText>(u"2"));
```

## موارد مرتبط

* نوع‌تعریف [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathPhantom](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
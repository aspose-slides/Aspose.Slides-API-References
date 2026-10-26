---
title: MathBox()
second_title: مرجع API Aspose.Slides برای C++
description: MathBox را با عنصر مشخص به‌عنوان آرگومان مقداردهی اولیه می‌کند
type: docs
weight: 144
url: /fa/aspose.slides.mathtext/mathbox/mathbox/
---
## MathBox::MathBox(System::SharedPtr\<IMathElement\>) سازنده

[MathBox](../) را با عنصر مشخص به‌عنوان آرگومان مقداردهی اولیه می‌کند

```cpp
Aspose::Slides::MathText::MathBox::MathBox(System::SharedPtr<IMathElement> element)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | العنصر پایه‌ای که جعبه به آن اعمال می‌شود. می‌تواند null باشد. |

## توضیحات



مثال: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathBox](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)
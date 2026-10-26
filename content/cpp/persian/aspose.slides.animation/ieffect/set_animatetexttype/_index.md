---
title: set_AnimateTextType()
second_title: مرجع API Aspose.Slides برای C++ 
description: یک نوع متن انیمیشن را برای افکت تعریف می‌کند. متن شکل می‌تواند به صورت حرف به حرف، به صورت کلمه به کلمه یا به‌صورت همزمان انیمیشن شود. AnimateTextType را بنویسید.
type: docs
weight: 287
url: /fa/aspose.slides.animation/ieffect/set_animatetexttype/
---
## IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) متد

یک نوع متن انیمیشن را برای افکت تعریف می‌کند. متن شکل می‌تواند به صورت حرف به حرف، به صورت کلمه به کلمه یا به‌صورت همزمان انیمیشن شود. [AnimateTextType](../../animatetexttype/) را بنویسید.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value)=0
```

## توضییات

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## موارد مرتبط

* شمارش [AnimateTextType](../../animatetexttype/)
* کلاس [IEffect](../)
* فضای نام [Aspose::Slides::Animation](../../)
* کتابخانه [Aspose.Slides](../../../)
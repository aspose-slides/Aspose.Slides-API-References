---
title: set_AnimateTextType()
second_title: مرجع API برای Aspose.Slides در C++
description: یک نوع متن انیمیشن را برای اثر تعریف می‌کند. متن شکل می‌تواند به صورت حرف به حرف، کلمه به کلمه یا به‌صورت کلی انیمیشن شود. AnimateTextType را بنویسید.
type: docs
weight: 287
url: /fa/aspose.slides.animation/effect/set_animatetexttype/
---
## Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) متد

یک نوع متن انیمیشن را برای اثر تعریف می‌کند. متن شکل می‌تواند به صورت حرف به حرف، کلمه به کلمه یا به طور کلی انیمیشن شود. [AnimateTextType](../../animatetexttype/) را بنویسید.

```cpp
void Aspose::Slides::Animation::Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value) override
```

## توضیحات

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## مراجع

* enum [AnimateTextType](../../animatetexttype/)
* کلاس [Effect](../)
* فضای‌نام [Aspose::Slides::Animation](../../)
* کتابخانه [Aspose.Slides](../../../)
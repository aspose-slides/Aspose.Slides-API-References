---
title: get_AnimateTextType()
second_title: مرجع API Aspose.Slides برای C++
description: یک نوع متن متحرک برای اثر تعریف می‌کند. متن شکل می‌تواند به صورت حرف، کلمه یا به‌صورت یکجا متحرک شود. مطالعه AnimateTextType.
type: docs
weight: 274
url: /fa/aspose.slides.animation/ieffect/get_animatetexttype/
---
## IEffect::get_AnimateTextType() متد


یک نوع متن متحرک برای اثر تعریف می‌کند. متن شکل می‌تواند به صورت حرف، کلمه یا به‌صورت یکجا متحرک شود. مطالعه [AnimateTextType](../../animatetexttype/).

```cpp
virtual Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::IEffect::get_AnimateTextType()=0
```

## ملاحظات



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## موارد مرتبط

* Enum [AnimateTextType](../../animatetexttype/)
* کلاس [IEffect](../)
* فضای نام [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)
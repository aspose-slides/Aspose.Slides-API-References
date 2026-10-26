---
title: get_AnimateTextType()
second_title: مرجع API Aspose.Slides برای C++
description: یک نوع متن متحرک برای اثر تعریف می‌کند. متن شکل می‌تواند بر حسب حرف، بر حسب کلمه یا به‌صورت کلی متحرک شود. برای اطلاعات بیشتر AnimateTextType را بخوانید.
type: docs
weight: 274
url: /fa/aspose.slides.animation/effect/get_animatetexttype/
---
## Effect::get_AnimateTextType() متد

یک نوع متن متحرک برای اثر تعریف می‌کند. متن شکل می‌تواند بر اساس حرف، بر اساس کلمه یا به‌صورت کلی متحرک شود. به [AnimateTextType](../../animatetexttype/) مراجعه کنید.

```cpp
Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::Effect::get_AnimateTextType() override
```

## توضیحاتی



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// دریافت اولین افکت اسلاید اول.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// تغییر نوع متن متحرک اثر به "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## موارد مرتبط

* Enum [AnimateTextType](../../animatetexttype/)
* کلاس [Effect](../)
* فضای‌نام [Aspose::Slides::Animation](../../)
* کتابخانه [Aspose.Slides](../../../)
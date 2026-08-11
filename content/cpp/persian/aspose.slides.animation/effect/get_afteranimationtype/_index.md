---
title: get_AfterAnimationType()
second_title: مرجع API Aspose.Slides برای C++
description: یک نوع انیمیشن پس از اثر را تعریف می‌کند. AfterAnimationType را بخوانید.
type: docs
weight: 222
url: /fa/aspose.slides.animation/effect/get_afteranimationtype/
---
## Effect::get_AfterAnimationType() متد

یک نوع انیمیشن پس از اثر را تعریف می‌کند. بخوانید [AfterAnimationType](../../afteranimationtype/).

```cpp
Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::Effect::get_AfterAnimationType() override
```

## توضیحات

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation to "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## موارد مرتبط

* enum [AfterAnimationType](../../afteranimationtype/)
* کلاس [Effect](../)
* فضای‌نام [Aspose::Slides::Animation](../../)
* کتابخانه [Aspose.Slides](../../../)
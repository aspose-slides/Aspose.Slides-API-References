---
title: set_AfterAnimationType()
second_title: مرجع API Aspose.Slides برای C++
description: یک نوع AfterAnimationType برای افکت تعریف می‌کند. AfterAnimationType را بنویسید.
type: docs
weight: 235
url: /fa/aspose.slides.animation/effect/set_afteranimationtype/
---
## Effect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) متد

یک نوع بعد از انیمیشن برای افکت تعریف می‌کند. [AfterAnimationType](../../afteranimationtype/) را بنویسید.

```cpp
void Aspose::Slides::Animation::Effect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value) override
```

## توضیحات



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation to "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## همچنین ببینید

* enum [AfterAnimationType](../../afteranimationtype/)
* کلاس [Effect](../)
* فضای نام [Aspose::Slides::Animation](../../)
* کتابخانه [Aspose.Slides](../../../)
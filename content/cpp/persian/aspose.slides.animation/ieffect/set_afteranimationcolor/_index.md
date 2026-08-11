---
title: set_AfterAnimationColor()
second_title: مرجع API Aspose.Slides برای C++
description: یک رنگ پس از انیمیشن برای اثر تعریف می‌کند. IColorFormat را بنویسید.
type: docs
weight: 261
url: /fa/aspose.slides.animation/ieffect/set_afteranimationcolor/
---
## IEffect::set_AfterAnimationColor(System::SharedPtr\<IColorFormat\>) متد


یک رنگ پس از انیمیشن برای اثر تعریف می‌کند. [IColorFormat](../../../aspose.slides/icolorformat/) را بنویسید.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationColor(System::SharedPtr<IColorFormat> value)=0
```

## توضیحات



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation type to "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Set the effect After animation color.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## مراجع مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IColorFormat](../../../aspose.slides/icolorformat/)
* کلاس [IEffect](../)
* فضای‌نام [Aspose::Slides::Animation](../../)
* کتابخانه [Aspose.Slides](../../../)
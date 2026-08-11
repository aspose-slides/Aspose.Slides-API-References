---
title: get_AfterAnimationColor()
second_title: مرجع API Aspose.Slides برای C++
description: یک رنگ پس از انیمیشن برای اثر تعریف شده است. IColorFormat را بخوانید.
type: docs
weight: 248
url: /fa/aspose.slides.animation/ieffect/get_afteranimationcolor/
---
## IEffect::get_AfterAnimationColor() متد


یک رنگ پس از انیمیشن برای اثر تعریف شده است. [IColorFormat](../../../aspose.slides/icolorformat/) را بخوانید.

```cpp
virtual System::SharedPtr<IColorFormat> Aspose::Slides::Animation::IEffect::get_AfterAnimationColor()=0
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

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColorFormat](../../../aspose.slides/icolorformat/)
* Class [IEffect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)
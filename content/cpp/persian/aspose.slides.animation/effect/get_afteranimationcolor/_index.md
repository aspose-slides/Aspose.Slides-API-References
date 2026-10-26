---
title: get_AfterAnimationColor()
second_title: مرجع API Aspose.Slides برای C++
description: یک رنگ پس از انیمیشن برای افکت تعریف می‌کند. IColorFormat را بخوانید.
type: docs
weight: 248
url: /fa/aspose.slides.animation/effect/get_afteranimationcolor/
---
## Effect::get_AfterAnimationColor() متد

یک رنگ پس از انیمیشن برای افکت تعریف می‌کند. [IColorFormat](../../../aspose.slides/icolorformat/) را بخوانید.

```cpp
System::SharedPtr<IColorFormat> Aspose::Slides::Animation::Effect::get_AfterAnimationColor() override
```

## توضیحات

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// دریافت اولین اثر از اولین اسلاید.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// تغییر نوع After animation اثر به "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// تنظیم رنگ After animation اثر.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## مراجع

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IColorFormat](../../../aspose.slides/icolorformat/)
* کلاس [Effect](../)
* فضای‌نام [Aspose::Slides::Animation](../../)
* کتابخانه [Aspose.Slides](../../../)
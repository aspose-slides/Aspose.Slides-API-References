---
title: get_AfterAnimationColor()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: تم تعريف لون بعد الرسوم المتحركة للتأثير. اقرأ IColorFormat.
type: docs
weight: 248
url: /ar/aspose.slides.animation/ieffect/get_afteranimationcolor/
---
## IEffect::get_AfterAnimationColor() طريقة

تم تعريف لون بعد الرسوم المتحركة للتأثير. اقرأ [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
virtual System::SharedPtr<IColorFormat> Aspose::Slides::Animation::IEffect::get_AfterAnimationColor()=0
```

## ملاحظات

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation type to "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Set the effect After animation color.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IColorFormat](../../../aspose.slides/icolorformat/)
* فئة [IEffect](../)
* مساحة الاسم [Aspose::Slides::Animation](../../)
* مكتبة [Aspose.Slides](../../../)
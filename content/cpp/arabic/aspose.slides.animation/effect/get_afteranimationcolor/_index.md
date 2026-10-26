---
title: get_AfterAnimationColor()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد لونًا بعد الرسوم المتحركة للتأثير. اقرأ IColorFormat.
type: docs
weight: 248
url: /ar/aspose.slides.animation/effect/get_afteranimationcolor/
---
## Effect::get_AfterAnimationColor() طريقة


يحدد لونًا ما بعد الرسوم المتحركة للتأثير. اقرأ [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
System::SharedPtr<IColorFormat> Aspose::Slides::Animation::Effect::get_AfterAnimationColor() override
```

## ملاحظات



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// احصل على التأثير الأول في الشريحة الأولى.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// غيّر نوع التأثير بعد الرسوم المتحركة إلى "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// عيّن لون التأثير بعد الرسوم المتحركة.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## انظر أيضًا

* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* فئة [IColorFormat](../../../aspose.slides/icolorformat/)
* فئة [Effect](../)
* نطاق [Aspose::Slides::Animation](../../)
* مكتبة [Aspose.Slides](../../../)
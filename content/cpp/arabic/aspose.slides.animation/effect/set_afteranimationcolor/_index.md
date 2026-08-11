---
title: set_AfterAnimationColor()
second_title: مرجع API Aspose.Slides للغة C++
description: يحدد لونًا بعد الرسوم المتحركة للتأثير. اكتب IColorFormat.
type: docs
weight: 261
url: /ar/aspose.slides.animation/effect/set_afteranimationcolor/
---
## Effect::set_AfterAnimationColor(System::SharedPtr\<IColorFormat\>) طريقة

يحدد لونًا بعد الرسوم المتحركة للتأثير. اكتب [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
void Aspose::Slides::Animation::Effect::set_AfterAnimationColor(System::SharedPtr<IColorFormat> value) override
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
* فئة [Effect](../)
* نطاق [Aspose::Slides::Animation](../../)
* مكتبة [Aspose.Slides](../../../)
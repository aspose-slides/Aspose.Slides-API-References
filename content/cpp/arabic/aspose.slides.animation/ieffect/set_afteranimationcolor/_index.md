---
title: set_AfterAnimationColor()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: تم تعريف لون بعد الرسوم المتحركة للتأثير. اكتب IColorFormat.
type: docs
weight: 261
url: /ar/aspose.slides.animation/ieffect/set_afteranimationcolor/
---
## IEffect::set_AfterAnimationColor(System::SharedPtr\<IColorFormat\>) طريقة


تم تعريف لون بعد الرسوم المتحركة للتأثير. اكتب [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationColor(System::SharedPtr<IColorFormat> value)=0
```

## ملاحظات



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// الحصول على التأثير الأول من الشريحة الأولى.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// تغيير نوع After animation للتأثير إلى "Color"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// تعيين لون After animation للتأثير.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IColorFormat](../../../aspose.slides/icolorformat/)
* فئة [IEffect](../)
* نطاق [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)
---
title: set_AfterAnimationType()
second_title: Aspose.Slides مرجع API للغة C++
description: تم تعريف نوع الرسوم المتحركة بعد التأثير. اكتب AfterAnimationType.
type: docs
weight: 235
url: /ar/aspose.slides.animation/ieffect/set_afteranimationtype/
---
## IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) طريقة


تم تعريف نوع الرسوم المتحركة بعد التأثير. اكتب [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value)=0
```

## ملاحظات



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation to "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## انظر أيضًا

* Enum [AfterAnimationType](../../afteranimationtype/)
* فئة [IEffect](../)
* مساحة اسم [Aspose::Slides::Animation](../../)
* مكتبة [Aspose.Slides](../../../)
---
title: get_AfterAnimationType()
second_title: Aspose.Slides لـ C++ مرجع API
description: تم تعريف نوع الرسوم المتحركة بعدية للتأثير. اقرأ AfterAnimationType.
type: docs
weight: 222
url: /ar/aspose.slides.animation/ieffect/get_afteranimationtype/
---
## IEffect::get_AfterAnimationType() طريقة


تم تعريف نوع الرسوم المتحركة بعدية للتأثير. اقرأ [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::IEffect::get_AfterAnimationType()=0
```

## ملاحظات



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// احصل على التأثير الأول للشريحة الأولى.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// غيّر تأثير الرسوم المتحركة بعدي إلى "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## راجع أيضا

* تعداد [AfterAnimationType](../../afteranimationtype/)
* فئة [IEffect](../)
* مساحة اسم [Aspose::Slides::Animation](../../)
* مكتبة [Aspose.Slides](../../../)
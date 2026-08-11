---
title: get_AfterAnimationType()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحدد نوع الرسوم المتحركة اللاحقة للتأثير. اقرأ AfterAnimationType.
type: docs
weight: 222
url: /ar/aspose.slides.animation/effect/get_afteranimationtype/
---
## Effect::get_AfterAnimationType() طريقة


يحدد نوع الرسوم المتحركة اللاحقة للتأثير. اقرأ [AfterAnimationType](../../afteranimationtype/).

```cpp
Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::Effect::get_AfterAnimationType() override
```

## ملاحظات



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// احصل على أول تأثير في الشريحة الأولى.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// غيّر تأثير After animation إلى "إخفاء عند النقر التالي على الفأرة"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## انظر أيضًا

* تعداد [AfterAnimationType](../../afteranimationtype/)
* فئة [Effect](../)
* نطاق [Aspose::Slides::Animation](../../)
* مكتبة [Aspose.Slides](../../../)
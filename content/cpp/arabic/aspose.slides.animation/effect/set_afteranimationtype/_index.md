---
title: set_AfterAnimationType()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحدد نوع الحركة بعد الرسوم المتحركة للتأثير. اكتب AfterAnimationType.
type: docs
weight: 235
url: /ar/aspose.slides.animation/effect/set_afteranimationtype/
---
## Effect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) طريقة

يحدد نوع الحركة بعد الرسوم المتحركة للتأثير. اكتب [AfterAnimationType](../../afteranimationtype/).

```cpp
void Aspose::Slides::Animation::Effect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value) override
```

## ملاحظات



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// احصل على التأثير الأول للشريحة الأولى.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// غيّر تأثير After animation إلى "إخفاء عند النقر التالي للماوس"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## انظر أيضاً

* Enum [AfterAnimationType](../../afteranimationtype/)
* Class [Effect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)
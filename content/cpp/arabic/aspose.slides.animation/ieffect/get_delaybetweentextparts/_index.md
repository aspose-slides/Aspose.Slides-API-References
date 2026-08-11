---
title: get_DelayBetweenTextParts()
second_title: مرجع API Aspose.Slides للغة C++
description: يعرف تأخيرًا بين أجزاء النص المتحركة (كلمات أو أحرف). القيمة الموجبة تحدد نسبة مئوية من مدة التأثير. القيمة السالبة تحدد التأخير بالثواني. اقرأ **float**.
type: docs
weight: 300
url: /ar/aspose.slides.animation/ieffect/get_delaybetweentextparts/
---
## IEffect::get_DelayBetweenTextParts() طريقة

يعرف تأخيرًا بين أجزاء النص المتحركة (كلمات أو أحرف). تُحدد القيمة الموجبة نسبة مئوية من مدة التأثير. تُحدد القيمة السالبة التأخير بالثواني. اقرأ **float**.

```cpp
virtual float Aspose::Slides::Animation::IEffect::get_DelayBetweenTextParts()=0
```

## ملاحظات

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By word"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Set the delay between animated text parts to 20% of effect duration.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## انظر أيضًا

* الفئة [IEffect](../)
* النطاق [Aspose::Slides::Animation](../../)
* المكتبة [Aspose.Slides](../../../)
---
title: get_DelayBetweenTextParts()
second_title: مرجع API Aspose.Slides للغة C++
description: يحدد تأخيرًا بين أجزاء النص المتحركة (كلمات أو حروف). القيمة الموجبة تحدد النسبة المئوية لمدة التأثير. القيمة السالبة تحدد التأخير بالثواني. اقرأ float.
type: docs
weight: 300
url: /ar/aspose.slides.animation/effect/get_delaybetweentextparts/
---
## Effect::get_DelayBetweenTextParts() طريقة

يُعرّف تأخيرًا بين أجزاء النص المتحركة (كلمات أو حروف). القيمة الموجبة تحدد النسبة المئوية لمدة التأثير. القيمة السالبة تحدد التأخير بالثواني. اقرأ **float**.

```cpp
float Aspose::Slides::Animation::Effect::get_DelayBetweenTextParts() override
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

* الفئة [Effect](../)
* النطاق [Aspose::Slides::Animation](../../)
* المكتبة [Aspose.Slides](../../../)
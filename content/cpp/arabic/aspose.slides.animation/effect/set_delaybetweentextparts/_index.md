---
title: set_DelayBetweenTextParts()
second_title: مرجع API Aspose.Slides للغة C++
description: يعرف تأخيرًا بين أجزاء النص المتحركة (كلمات أو أحرف). القيمة الموجبة تحدد نسبة مدة التأثير. القيمة السالبة تحدد التأخير بالثواني. اكتب float.
type: docs
weight: 313
url: /ar/aspose.slides.animation/effect/set_delaybetweentextparts/
---
## Effect::set_DelayBetweenTextParts(float) طريقة

يحدد تأخيرًا بين أقسام النص المتحركة (الكلمات أو الحروف). القيمة الموجبة تحدد النسبة المئوية لمدة التأثير. القيمة السالبة تحدد التأخير بالثواني. اكتب **float**.

```cpp
void Aspose::Slides::Animation::Effect::set_DelayBetweenTextParts(float value) override
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

* فئة [Effect](../)
* مساحة الاسم [Aspose::Slides::Animation](../../)
* مكتبة [Aspose.Slides](../../../)
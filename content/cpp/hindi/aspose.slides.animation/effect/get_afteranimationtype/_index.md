---
title: get_AfterAnimationType()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: प्रभाव के लिए एक बाद एनीमेशन प्रकार को परिभाषित करता है। पढ़ें AfterAnimationType.
type: docs
weight: 222
url: /hi/aspose.slides.animation/effect/get_afteranimationtype/
---
## Effect::get_AfterAnimationType() मेथड


प्रभाव के लिए एक बाद एनीमेशन प्रकार को परिभाषित करता है। पढ़ें [AfterAnimationType](../../afteranimationtype/).

```cpp
Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::Effect::get_AfterAnimationType() override
```

## टिप्पणियाँ


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation to "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## देखें

* एन्यूम [AfterAnimationType](../../afteranimationtype/)
* क्लास [Effect](../)
* नेमस्पेस [Aspose::Slides::Animation](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
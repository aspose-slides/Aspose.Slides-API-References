---
title: set_AfterAnimationType()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: प्रभाव के लिए एक आफ्टर एनीमेशन प्रकार परिभाषित करता है। लिखें AfterAnimationType.
type: docs
weight: 235
url: /hi/aspose.slides.animation/effect/set_afteranimationtype/
---
## Effect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) विधि

प्रभाव के लिए एक आफ्टर एनिमेशन प्रकार परिभाषित करता है। लिखें [AfterAnimationType](../../afteranimationtype/).

```cpp
void Aspose::Slides::Animation::Effect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value) override
```

## टिप्पणी

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// पहली स्लाइड के पहले इफ़ेक्ट को प्राप्त करें।
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// इफ़ेक्ट की After animation को "Hide on Next Mouse Click" में बदलें।
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## देखें

* एन्युम [AfterAnimationType](../../afteranimationtype/)
* क्लास [Effect](../)
* नेमस्पेस [Aspose::Slides::Animation](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
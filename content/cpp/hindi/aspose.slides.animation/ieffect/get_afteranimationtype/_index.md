---
title: get_AfterAnimationType()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: इफ़ेक्ट के लिए एक बाद-की एनीमेशन प्रकार निर्धारित किया गया है। पढ़ें AfterAnimationType।
type: docs
weight: 222
url: /hi/aspose.slides.animation/ieffect/get_afteranimationtype/
---
## IEffect::get_AfterAnimationType() मेथड


इफ़ेक्ट के लिए एक बाद-की एनीमेशन प्रकार निर्धारित किया गया है। पढ़ें [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::IEffect::get_AfterAnimationType()=0
```

## टिप्पणियाँ



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// पहले स्लाइड का पहला प्रभाव प्राप्त करें।
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// प्रभाव के After animation को "Hide on Next Mouse Click" में बदलें
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## संबंधित देखें

* Enum [AfterAnimationType](../../afteranimationtype/)
* क्लास [IEffect](../)
* नेमस्पेस [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)
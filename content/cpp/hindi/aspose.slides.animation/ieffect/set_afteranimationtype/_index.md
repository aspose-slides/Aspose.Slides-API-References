---
title: set_AfterAnimationType()
second_title: Aspose.Slides for C++ API संदर्भ
description: इफ़ेक्ट के लिए एक बाद का एनीमेशन प्रकार परिभाषित किया गया। लिखें AfterAnimationType.
type: docs
weight: 235
url: /hi/aspose.slides.animation/ieffect/set_afteranimationtype/
---
## IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) विधि

इफ़ेक्ट के लिए एक बाद का एनीमेशन प्रकार परिभाषित किया गया। लिखें [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value)=0
```

## टिप्पणियाँ

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// पहले स्लाइड के पहले प्रभाव को प्राप्त करें।
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// प्रभाव After animation को "Hide on Next Mouse Click" में बदलें
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## देखें

* Enum [AfterAnimationType](../../afteranimationtype/)
* क्लास [IEffect](../)
* नामस्थान [Aspose::Slides::Animation](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
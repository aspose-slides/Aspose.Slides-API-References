---
title: get_AnimateTextType()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: प्रभाव के लिए एनीमेट टेक्स्ट प्रकार को परिभाषित करता है। आकार का टेक्स्ट अक्षर द्वारा, शब्द द्वारा या सभी एक साथ एनीमेट किया जा सकता है। AnimateTextType पढ़ें।
type: docs
weight: 274
url: /hi/aspose.slides.animation/ieffect/get_animatetexttype/
---
## IEffect::get_AnimateTextType() विधि


प्रभाव के लिए एनीमेट टेक्स्ट प्रकार को परिभाषित करता है। आकृति का टेक्स्ट अक्षर द्वारा, शब्द द्वारा या सभी एक साथ एनीमेट किया जा सकता है। पढ़ें [AnimateTextType](../../animatetexttype/)।

```cpp
virtual Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::IEffect::get_AnimateTextType()=0
```

## टिप्पणी



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// पहले स्लाइड का पहला इफ़ेक्ट प्राप्त करें।
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// इफ़ेक्ट के एनीमेट टेक्स्ट प्रकार को "By letter" में बदलें।
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## संबंधित देखें

* Enum [AnimateTextType](../../animatetexttype/)
* वर्ग [IEffect](../)
* नेमस्पेस [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)
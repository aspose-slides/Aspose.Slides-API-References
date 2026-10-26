---
title: set_AnimateTextType()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: इफ़ेक्ट के लिए एनीमेट टेक्स्ट टाइप को परिभाषित करता है। शेप टेक्स्ट को अक्षर द्वारा, शब्द द्वारा या एक साथ एनीमेट किया जा सकता है। लिखें AnimateTextType.
type: docs
weight: 287
url: /hi/aspose.slides.animation/effect/set_animatetexttype/
---
## Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) विधि


इफ़ेक्ट के लिए एनीमेट टेक्स्ट टाइप को परिभाषित करता है। शेप टेक्स्ट को अक्षर द्वारा, शब्द द्वारा या एक साथ एनीमेट किया जा सकता है। लिखें [AnimateTextType](../../animatetexttype/).

```cpp
void Aspose::Slides::Animation::Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value) override
```

## टिप्पणियाँ



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## सम्बंधित देखें

* एन्यूम [AnimateTextType](../../animatetexttype/)
* क्लास [Effect](../)
* नामस्थान [Aspose::Slides::Animation](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
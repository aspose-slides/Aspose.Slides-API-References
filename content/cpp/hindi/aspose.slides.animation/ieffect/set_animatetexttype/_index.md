---
title: set_AnimateTextType()
second_title: Aspose.Slides for C++ API संदर्भ
description: इफ़ेक्ट के लिए एनीमेट टेक्स्ट टाइप को परिभाषित करता है। शेप टेक्स्ट को अक्षर दर अक्षर, शब्द दर शब्द या एक साथ एनीमेट किया जा सकता है। लिखें AnimateTextType.
type: docs
weight: 287
url: /hi/aspose.slides.animation/ieffect/set_animatetexttype/
---
## IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) मेथड


इफ़ेक्ट के लिए एनीमेट टेक्स्ट टाइप को परिभाषित करता है। शेप टेक्स्ट को अक्षर दर अक्षर, शब्द दर शब्द या एक साथ एनीमेट किया जा सकता है। लिखें [AnimateTextType](../../animatetexttype/)।

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value)=0
```

## टिप्पणियाँ



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## संबंधित देखें

* Enum [AnimateTextType](../../animatetexttype/)
* Class [IEffect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)
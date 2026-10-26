---
title: get_AnimateTextType()
second_title: Aspose.Slides for C++ API संदर्भ
description: इफ़ेक्ट के लिए एनीमेट टेक्स्ट टाइप को परिभाषित करता है। आकार के टेक्स्ट को अक्षर अनुसार, शब्द अनुसार या एक साथ सभी को एनीमेट किया जा सकता है। पढ़ें AnimateTextType।
type: docs
weight: 274
url: /hi/aspose.slides.animation/effect/get_animatetexttype/
---
## Effect::get_AnimateTextType() मेथड


इफेक्ट के लिए एनीमेट टेक्स्ट टाइप को परिभाषित करता है। आकार के टेक्स्ट को अक्षर अनुसार, शब्द अनुसार या एक साथ सभी को एनीमेट किया जा सकता है। पढ़ें [AnimateTextType](../../animatetexttype/)।

```cpp
Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::Effect::get_AnimateTextType() override
```

## टिप्पणियाँ



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## देखें

* Enum [AnimateTextType](../../animatetexttype/)
* Class [Effect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)
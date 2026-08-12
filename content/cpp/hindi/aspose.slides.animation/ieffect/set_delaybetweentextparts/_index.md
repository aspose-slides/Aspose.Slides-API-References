---
title: set_DelayBetweenTextParts()
second_title: Aspose.Slides for C++ API संदर्भ
description: एनिमेटेड टेक्स्ट भागों (शब्दों या अक्षरों) के बीच विलंब को परिभाषित करता है। एक सकारात्मक मान प्रभाव की अवधि का प्रतिशत निर्दिष्ट करता है। एक नकारात्मक मान सेकंड में विलंब को निर्दिष्ट करता है। लिखें float।
type: docs
weight: 313
url: /hi/aspose.slides.animation/ieffect/set_delaybetweentextparts/
---
## IEffect::set_DelayBetweenTextParts(float) विधि

एनिमेटेड टेक्स्ट भागों (शब्दों या अक्षरों) के बीच विलंब को परिभाषित करता है। एक सकारात्मक मान प्रभाव की अवधि का प्रतिशत बताता है। एक नकारात्मक मान सेकंड में विलंब को निर्दिष्ट करता है। लिखें **float**।

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_DelayBetweenTextParts(float value)=0
```

## टिप्पणी



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By word"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Set the delay between animated text parts to 20% of effect duration.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## देखें

* क्लास [IEffect](../)
* नामस्थान [Aspose::Slides::Animation](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
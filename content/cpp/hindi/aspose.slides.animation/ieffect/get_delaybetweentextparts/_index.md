---
title: get_DelayBetweenTextParts()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एनिमेटेड टेक्स्ट भागों (शब्द या अक्षर) के बीच एक विलंब को निर्धारित करता है। एक सकारात्मक मान प्रभाव की अवधि का प्रतिशत निर्दिष्ट करता है। एक नकारात्मक मान सेकंड में विलंब को निर्दिष्ट करता है। पढ़ें float.
type: docs
weight: 300
url: /hi/aspose.slides.animation/ieffect/get_delaybetweentextparts/
---
## IEffect::get_DelayBetweenTextParts() मेथड


परिभाषित करता है एक विलंब को एनीमेटेड टेक्स्ट भागों (शब्दों या अक्षरों) के बीच। एक सकारात्मक मान प्रभाव की अवधि का प्रतिशत निर्दिष्ट करता है। एक नकारात्मक मान सेकंड में विलंब को निर्दिष्ट करता है। पढ़ें **float**.

```cpp
virtual float Aspose::Slides::Animation::IEffect::get_DelayBetweenTextParts()=0
```

## टिप्पणियाँ



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
* नेमस्पेस [Aspose::Slides::Animation](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
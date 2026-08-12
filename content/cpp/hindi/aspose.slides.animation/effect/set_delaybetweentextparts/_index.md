---
title: set_DelayBetweenTextParts()
second_title: Aspose.Slides C++ के लिए API रेफ़रेंस
description: परिभाषित करता है एनीमेटेड टेक्स्ट भागों (शब्द या अक्षर) के बीच एक देरी को। एक सकारात्मक मान प्रभाव अवधि का प्रतिशत निर्दिष्ट करता है। एक नकारात्मक मान सेकंड में देरी निर्दिष्ट करता है। लिखें float।
type: docs
weight: 313
url: /hi/aspose.slides.animation/effect/set_delaybetweentextparts/
---
## Effect::set_DelayBetweenTextParts(float) मेथड

परिभाषित करता है एक देरी को एनीमेटेड टेक्स्ट भागों (शब्द या अक्षर) के बीच। एक सकारात्मक मान प्रभाव अवधि का प्रतिशत निर्दिष्ट करता है। एक नकारात्मक मान सेकंड में देरी निर्दिष्ट करता है। लिखें **float**।

```cpp
void Aspose::Slides::Animation::Effect::set_DelayBetweenTextParts(float value) override
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

## संबंधित देखें

* क्लास [Effect](../)
* नेमस्पेस [Aspose::Slides::Animation](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
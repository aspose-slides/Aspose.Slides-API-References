---
title: get_DelayBetweenTextParts()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एनिमेटेड टेक्स्ट भागों (शब्द या अक्षर) के बीच देरी को परिभाषित करता है। एक सकारात्मक मान प्रभाव की अवधि का प्रतिशत निर्दिष्ट करता है। एक नकारात्मक मान सेकंड में देरी को निर्दिष्ट करता है। पढ़ें float.
type: docs
weight: 300
url: /hi/aspose.slides.animation/effect/get_delaybetweentextparts/
---
## Effect::get_DelayBetweenTextParts() विधि


एनिमेटेड टेक्स्ट भागों (शब्द या अक्षर) के बीच देरी को परिभाषित करता है। एक सकारात्मक मान प्रभाव की अवधि का प्रतिशत निर्दिष्ट करता है। एक नकारात्मक मान सेकंड में देरी को निर्दिष्ट करता है। पढ़ें **float**.

```cpp
float Aspose::Slides::Animation::Effect::get_DelayBetweenTextParts() override
```

## टिप्पणियाँ



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// पहले स्लाइड का पहला इफ़ेक्ट प्राप्त करें।
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// इफ़ेक्ट के एनीमेट टेक्स्ट प्रकार को "By word" में बदलें।
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// एनिमेटेड टेक्स्ट भागों के बीच देरी को प्रभाव अवधि के 20% पर सेट करें।
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## संबंधित देखें

* क्लास [Effect](../)
* नामस्थान [Aspose::Slides::Animation](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
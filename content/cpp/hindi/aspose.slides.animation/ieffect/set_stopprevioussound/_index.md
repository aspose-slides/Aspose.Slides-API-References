---
title: set_StopPreviousSound()
second_title: Aspose.Slides for C++ API संदर्भ
description: यह विशेषता निर्दिष्ट करती है कि क्या एनीमेशन प्रभाव पहले की ध्वनि को रोकता है। लिखें bool.
type: docs
weight: 209
url: /hi/aspose.slides.animation/ieffect/set_stopprevioussound/
---
## IEffect::set_StopPreviousSound(bool) विधि

यह विशेषता निर्दिष्ट करती है कि क्या एनीमेशन प्रभाव पिछले ध्वनि को रोकता है। लिखें **bool**.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_StopPreviousSound(bool value)=0
```

## टिप्पणी

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// पहले स्लाइड का पहला इफ़ेक्ट प्राप्त करें।
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// दूसरे स्लाइड का पहला इफ़ेक्ट प्राप्त करें।
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // दूसरे इफ़ेक्ट Enhancements/Sound को "Stop Previous Sound" में बदलें
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## संबंधित देखें

* क्लास [IEffect](../)
* नेमस्पेस [Aspose::Slides::Animation](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
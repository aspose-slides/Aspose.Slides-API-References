---
title: get_StopPreviousSound()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: यह विशेषता निर्दिष्ट करती है कि क्या एनिमेशन प्रभाव पिछली ध्वनि को रोकता है। पढ़ें bool.
type: docs
weight: 196
url: /hi/aspose.slides.animation/ieffect/get_stopprevioussound/
---
## IEffect::get_StopPreviousSound() विधि


यह विशेषता निर्दिष्ट करती है कि क्या एनिमेशन प्रभाव पिछली ध्वनि को रोकता है। पढ़ें **bool**.

```cpp
virtual bool Aspose::Slides::Animation::IEffect::get_StopPreviousSound()=0
```

## टिप्पणी



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// पहला स्लाइड का पहला इफ़ेक्ट प्राप्त करें।
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// दूसरा स्लाइड का पहला इफ़ेक्ट प्राप्त करें।
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // दूसरे इफ़ेक्ट को Enhancements/Sound में "Stop Previous Sound" सेट करें
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## देखें

* क्लास [IEffect](../)
* नामस्थान [Aspose::Slides::Animation](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
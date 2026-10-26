---
title: get_StopPreviousSound()
second_title: Aspose.Slides for C++ API संदर्भ
description: यह विशेषता निर्धारित करती है कि क्या एनीमेशन इफ़ेक्ट पिछले ध्वनि को रोकता है। पढ़ें bool।
type: docs
weight: 196
url: /hi/aspose.slides.animation/effect/get_stopprevioussound/
---
## Effect::get_StopPreviousSound() मेथड


यह विशेषता निर्दिष्ट करती है कि क्या एनिमेशन इफ़ेक्ट पिछले ध्वनि को रोकता है। पढ़ें **bool**.

```cpp
bool Aspose::Slides::Animation::Effect::get_StopPreviousSound() override
```

## टिप्पणियाँ



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// पहला स्लाइड का पहला प्रभाव प्राप्त करें।
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// दूसरा स्लाइड का पहला प्रभाव प्राप्त करें।
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // दूसरे प्रभाव Enhancements/Sound को "Stop Previous Sound" में बदलें
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## संबंधित देखें

* क्लास [Effect](../)
* नामस्थान [Aspose::Slides::Animation](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
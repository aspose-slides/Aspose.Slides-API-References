---
title: set_StopPreviousSound()
second_title: Aspose.Slides for C++ API संदर्भ
description: यह विशेषता निर्धारित करती है कि क्या एनीमेशन इफ़ेक्ट पिछले ध्वनि को रोकता है। लिखें bool।
type: docs
weight: 209
url: /hi/aspose.slides.animation/effect/set_stopprevioussound/
---
## Effect::set_StopPreviousSound(bool) विधि


यह विशेषता बताती है कि क्या एनीमेशन इफ़ेक्ट पहले की ध्वनि को रोकता है। लिखें **bool**.

```cpp
void Aspose::Slides::Animation::Effect::set_StopPreviousSound(bool value) override
```

## टिप्पणियाँ



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// पहले स्लाइड के पहले इफ़ेक्ट को प्राप्त करें।
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// दूसरे स्लाइड के पहले इफ़ेक्ट को प्राप्त करें।
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // दूसरे इफ़ेक्ट Enhancements/Sound को "Stop Previous Sound" में बदलें
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## संबंधित देखें

* क्लास [Effect](../)
* नामस्थान [Aspose::Slides::Animation](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
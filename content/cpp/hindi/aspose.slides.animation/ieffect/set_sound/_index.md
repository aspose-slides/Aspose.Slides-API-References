---
title: set_Sound()
second_title: Aspose.Slides का C++ API संदर्भ
description: इफ़ेक्ट के लिए एम्बेडेड ध्वनि निर्धारित की गई। IAudio लिखें।
type: docs
weight: 183
url: /hi/aspose.slides.animation/ieffect/set_sound/
---
## IEffect::set_Sound(System::SharedPtr\<IAudio\>) विधि


प्रभाव के लिए एम्बेडेड ध्वनि निर्धारित किया गया। लिखें [IAudio](../../../aspose.slides/iaudio/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_Sound(System::SharedPtr<IAudio> value)=0
```

## टिप्पणियाँ



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// स्लाइड के लिए इफ़ेक्ट सीक्वेंस प्राप्त करता है
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // बाइट एरे में इफ़ेक्ट ध्वनि निकालता है
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IAudio](../../../aspose.slides/iaudio/)
* क्लास [IEffect](../)
* नेमस्पेस [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)
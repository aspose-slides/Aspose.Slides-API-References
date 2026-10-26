---
title: get_Sound()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: प्रभाव के लिए निर्धारित एम्बेडेड ध्वनि। पढ़ें IAudio।
type: docs
weight: 170
url: /hi/aspose.slides.animation/effect/get_sound/
---
## Effect::get_Sound() विधि


प्रभाव के लिए निर्धारित एम्बेडेड ध्वनि। पढ़ें [IAudio](../../../aspose.slides/iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Animation::Effect::get_Sound() override
```

## टिप्पणी



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// स्लाइड के प्रभाव अनुक्रम को प्राप्त करता है
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // इफ़ेक्ट ध्वनि को बाइट एरे में निकालता है
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```




## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IAudio](../../../aspose.slides/iaudio/)
* क्लास [Effect](../)
* नामस्थान [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)
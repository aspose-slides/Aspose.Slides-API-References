---
title: set_Sound()
second_title: Aspose.Slides for C++ API संदर्भ
description: इफ़ेक्ट के लिए एम्बेडेड साउंड को परिभाषित किया गया। IAudio लिखें।
type: docs
weight: 183
url: /hi/aspose.slides.animation/effect/set_sound/
---
## Effect::set_Sound(System::SharedPtr\<IAudio\>) विधि


इफ़ेक्ट के लिए एम्बेडेड साउंड को परिभाषित किया गया। [IAudio](../../../aspose.slides/iaudio/) लिखें।

```cpp
void Aspose::Slides::Animation::Effect::set_Sound(System::SharedPtr<IAudio> value) override
```

## टिप्पणियाँ



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// स्लाइड के लिए इफ़ेक्ट्स अनुक्रम प्राप्त करता है
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // इफ़ेक्ट साउंड को बाइट ऐरे में निकालता है
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```




## और देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IAudio](../../../aspose.slides/iaudio/)
* क्लास [Effect](../)
* नामस्थान [Aspose::Slides::Animation](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
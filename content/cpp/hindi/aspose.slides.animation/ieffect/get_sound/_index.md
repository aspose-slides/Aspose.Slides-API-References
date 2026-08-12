---
title: get_Sound()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: परिणाम के लिए परिभाषित एंबेडेड साउंड। IAudio पढ़ें।
type: docs
weight: 170
url: /hi/aspose.slides.animation/ieffect/get_sound/
---
## IEffect::get_Sound() विधि


परिणाम के लिए परिभाषित एंबेडेड साउंड। पढ़ें [IAudio](../../../aspose.slides/iaudio/).

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::Animation::IEffect::get_Sound()=0
```

## टिप्पणियाँ



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// स्लाइड के लिए प्रभाव क्रम प्राप्त करता है
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // प्रभाव ध्वनि को बाइट एरे में निकालता है
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudio](../../../aspose.slides/iaudio/)
* Class [IEffect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)
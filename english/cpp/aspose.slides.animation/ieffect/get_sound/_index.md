---
title: get_Sound()
second_title: Aspose.Slides for C++ API Reference
description: Defined embedded sound for effect. Read IAudio.
type: docs
weight: 170
url: /cpp/aspose.slides.animation/ieffect/get_sound/
---
## IEffect::get_Sound() method


Defined embedded sound for effect. Read [IAudio](../../../aspose.slides/iaudio/).

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::Animation::IEffect::get_Sound()=0
```

## Remarks



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// Gets the effects sequence for the slide
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // Extracts the effect sound in byte array
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudio](../../../aspose.slides/iaudio/)
* Class [IEffect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)
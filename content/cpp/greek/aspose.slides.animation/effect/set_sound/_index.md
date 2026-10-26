---
title: set_Sound()
second_title: Aspose.Slides για το API αναφοράς C++
description: Ορίστηκε ενσωματωμένος ήχος για το εφέ. Γράψτε IAudio.
type: docs
weight: 183
url: /el/aspose.slides.animation/effect/set_sound/
---
## Effect::set_Sound(System::SharedPtr\<IAudio\>) μέθοδος


Ορισμένο ενσωματωμένο ήχο για το εφέ. Γράψτε [IAudio](../../../aspose.slides/iaudio/).

```cpp
void Aspose::Slides::Animation::Effect::set_Sound(System::SharedPtr<IAudio> value) override
```

## Παρατηρήσεις



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// Λαμβάνει τη σειρά εφέ για τη διαφάνεια
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // Εξάγει τον ήχο του εφέ σε πίνακα byte
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```




## Δείτε επίσης

* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [IAudio](../../../aspose.slides/iaudio/)
* Κλάση [Effect](../)
* Χώρος ονομάτων [Aspose::Slides::Animation](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
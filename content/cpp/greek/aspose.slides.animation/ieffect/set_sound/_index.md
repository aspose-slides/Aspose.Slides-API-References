---
title: set_Sound()
second_title: Αναφορά API Aspose.Slides για C++
description: Ορίστηκε ενσωματωμένος ήχος για το εφέ. Γράψτε IAudio.
type: docs
weight: 183
url: /el/aspose.slides.animation/ieffect/set_sound/
---
## IEffect::set_Sound(System::SharedPtr\<IAudio\>) μέθοδος


Ορίστηκε ενσωματωμένος ήχος για το εφέ. Γράψτε [IAudio](../../../aspose.slides/iaudio/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_Sound(System::SharedPtr<IAudio> value)=0
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IAudio](../../../aspose.slides/iaudio/)
* Κλάση [IEffect](../)
* Χώρος ονομάτων [Aspose::Slides::Animation](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
---
title: get_Sound()
second_title: Αναφορά API Aspose.Slides για C++
description: Καθορίστηκε ενσωματωμένος ήχος για το εφέ. Διαβάστε IAudio.
type: docs
weight: 170
url: /el/aspose.slides.animation/ieffect/get_sound/
---
## IEffect::get_Sound() μέθοδος

Καθορίστηκε ενσωματωμένος ήχος για το εφέ. Διαβάστε [IAudio](../../../aspose.slides/iaudio/).

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::Animation::IEffect::get_Sound()=0
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

    // Εξάγει τον ήχο του εφέ σε πίνακα bytes
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## Δείτε επίσης

* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [IAudio](../../../aspose.slides/iaudio/)
* Κλάση [IEffect](../)
* Χώρος ονομάτων [Aspose::Slides::Animation](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
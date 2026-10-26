---
title: get_Sound()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ορίζεται ενσωματωμένος ήχος για το εφέ. Διαβάστε IAudio.
type: docs
weight: 170
url: /el/aspose.slides.animation/effect/get_sound/
---
## Effect::get_Sound() μέθοδος


Ορίζεται ενσωματωμένος ήχος για το εφέ. Διαβάστε [IAudio](../../../aspose.slides/iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Animation::Effect::get_Sound() override
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IAudio](../../../aspose.slides/iaudio/)
* Κλάση [Effect](../)
* Χώρος ονομάτων [Aspose::Slides::Animation](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
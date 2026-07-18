---
title: get_StopPreviousSound()
second_title: Αναφορά API του Aspose.Slides για C++
description: Αυτή η ιδιότητα καθορίζει αν το εφέ κίνησης σταματά τον προηγούμενο ήχο. Ανάγνωση bool.
type: docs
weight: 196
url: /el/aspose.slides.animation/effect/get_stopprevioussound/
---
## Effect::get_StopPreviousSound() μέθοδος


Αυτή η ιδιότητα καθορίζει αν το εφέ της κίνησης σταματά τον προηγούμενο ήχο. Ανάγνωση **bool**.

```cpp
bool Aspose::Slides::Animation::Effect::get_StopPreviousSound() override
```

## Παρατηρήσεις



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Λάβετε το πρώτο εφέ της πρώτης διαφάνειας.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// Λάβετε το πρώτο εφέ της δεύτερης διαφάνειας.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // Αλλάξτε το δεύτερο εφέ Enhancements/Sound σε "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## Δείτε επίσης

* Κλάση [Effect](../)
* Χώρος ονομάτων [Aspose::Slides::Animation](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
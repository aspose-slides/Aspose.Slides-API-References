---
title: set_StopPreviousSound()
second_title: Aspose.Slides για C++ Αναφορά API
description: Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ κίνησης σταματά τον προηγούμενο ήχο. Γράψτε bool.
type: docs
weight: 209
url: /el/aspose.slides.animation/effect/set_stopprevioussound/
---
## Effect::set_StopPreviousSound(bool) μέθοδος

Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ κίνησης σταματά τον προηγούμενο ήχο. Γράψτε **bool**.

```cpp
void Aspose::Slides::Animation::Effect::set_StopPreviousSound(bool value) override
```

## Παρατηρήσεις

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Πάρτε το πρώτο εφέ της πρώτης διαφάνειας.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// Πάρτε το πρώτο εφέ της δεύτερης διαφάνειας.
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
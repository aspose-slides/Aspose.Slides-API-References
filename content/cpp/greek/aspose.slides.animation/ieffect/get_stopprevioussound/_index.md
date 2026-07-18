---
title: get_StopPreviousSound()
second_title: Αναφορά API Aspose.Slides για C++
description: Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ κίνησης διακόπτει τον προηγούμενο ήχο. Διαβάστε bool.
type: docs
weight: 196
url: /el/aspose.slides.animation/ieffect/get_stopprevioussound/
---
## IEffect::get_StopPreviousSound() μέθοδος

Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ κίνησης διακόπτει τον προηγούμενο ήχο. Διαβάστε **bool**.

```cpp
virtual bool Aspose::Slides::Animation::IEffect::get_StopPreviousSound()=0
```

## Σχόλια

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

* Κλάση [IEffect](../)
* Χώρος ονομάτων [Aspose::Slides::Animation](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
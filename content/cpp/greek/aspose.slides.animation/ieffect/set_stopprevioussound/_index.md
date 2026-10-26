---
title: set_StopPreviousSound()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ κίνησης σταματά τον προηγούμενο ήχο. Γράψτε bool.
type: docs
weight: 209
url: /el/aspose.slides.animation/ieffect/set_stopprevioussound/
---
## IEffect::set_StopPreviousSound(bool) μέθοδος


Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ κίνησης σταματά τον προηγούμενο ήχο. Γράψτε **bool**.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_StopPreviousSound(bool value)=0
```

## Παρατηρήσεις



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Αποκτήστε το πρώτο εφέ της πρώτης διαφάνειας.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// Αποκτήστε το πρώτο εφέ της δεύτερης διαφάνειας.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // Αλλάξτε το δεύτερο εφέ Enhancements/Sound σε "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## Δείτε επίσης

* Κλάση [IEffect](../)
* Ονομαχώρος [Aspose::Slides::Animation](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
---
title: get_RepeatUntilEndSlide()
second_title: Aspose.Slides για C++ Αναφορά API
description: Αυτό το χαρακτηριστικό καθορίζει αν το εφέ θα επαναλαμβάνεται μέχρι το τέλος της διαφάνειας. Διαβάστε bool.
type: docs
weight: 131
url: /el/aspose.slides.animation/itiming/get_repeatuntilendslide/
---
## ITiming::get_RepeatUntilEndSlide() μέθοδος


Αυτό το χαρακτηριστικό καθορίζει αν το εφέ θα επαναλαμβάνεται έως το τέλος της διαφάνειας. Διαβάστε **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilEndSlide()=0
```

## Παρατηρήσεις



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Παίρνει τη σειρά εφέ για την πρώτη διαφάνεια
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Παίρνει το πρώτο εφέ της κύριας σειράς.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Αλλάζει το Timing/Repeat του εφέ σε "Until End of Slide"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## Δείτε επίσης

* Κλάση [ITiming](../)
* Χώρος ονομάτων [Aspose::Slides::Animation](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
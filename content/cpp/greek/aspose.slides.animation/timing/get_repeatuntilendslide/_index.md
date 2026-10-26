---
title: get_RepeatUntilEndSlide()
second_title: Aspose.Slides για την αναφορά API C++
description: Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επαναλαμβάνεται μέχρι το τέλος της διαφάνειας. Διαβάστε bool.
type: docs
weight: 131
url: /el/aspose.slides.animation/timing/get_repeatuntilendslide/
---
## Timing::get_RepeatUntilEndSlide() μέθοδος


Αυτό το χαρακτηριστικό καθορίζει αν το εφέ θα επαναλαμβάνεται μέχρι το τέλος της διαφάνειας. Ανάγνωση **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_RepeatUntilEndSlide() override
```

## Παρατηρήσεις



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Αποκτά τη σειρά εφέ για την πρώτη διαφάνεια
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Αποκτά το πρώτο εφέ της κύριας σειράς.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Αλλάζει το Timing/Repeat του εφέ σε "Until End of Slide"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## Δείτε επίσης

* Κλάση [Timing](../)
* Χώρος ονομάτων [Aspose::Slides::Animation](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
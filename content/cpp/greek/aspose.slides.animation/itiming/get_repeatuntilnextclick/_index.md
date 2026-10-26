---
title: get_RepeatUntilNextClick()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επαναληφθεί μέχρι το επόμενο κλικ. Ανάγνωση bool.
type: docs
weight: 157
url: /el/aspose.slides.animation/itiming/get_repeatuntilnextclick/
---
## ITiming::get_RepeatUntilNextClick() μέθοδος


Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επαναληφθεί μέχρι το επόμενο κλικ. Ανάγνωση **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilNextClick()=0
```

## Σχόλια



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Λαμβάνει τη σειρά εφέ για την πρώτη διαφάνεια
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Λαμβάνει το πρώτο εφέ της κύριας σειράς.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Αλλάζει το Timing/Repeat του εφέ σε "Until End of Slide"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## Δείτε επίσης

* Κλάση [ITiming](../)
* Χώρος ονομάτων [Aspose::Slides::Animation](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
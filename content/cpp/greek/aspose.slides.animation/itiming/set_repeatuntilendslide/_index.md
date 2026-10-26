---
title: set_RepeatUntilEndSlide()
second_title: Aspose.Slides για C++ Αναφορά API
description: Αυτό το χαρακτηριστικό καθορίζει αν το εφέ θα επαναλαμβάνεται μέχρι το τέλος της διαφάνειας. Γράψτε bool.
type: docs
weight: 144
url: /el/aspose.slides.animation/itiming/set_repeatuntilendslide/
---
## ITTiming::set_RepeatUntilEndSlide(bool) μέθοδος


Αυτό το χαρακτηριστικό καθορίζει αν το εφέ θα επαναλαμβάνεται μέχρι το τέλος της διαφάνειας. Γράψτε **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_RepeatUntilEndSlide(bool value)=0
```

## Παρατηρήσεις



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## Δείτε επίσης

* Κλάση [ITiming](../)
* Χώρος ονομάτων [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)
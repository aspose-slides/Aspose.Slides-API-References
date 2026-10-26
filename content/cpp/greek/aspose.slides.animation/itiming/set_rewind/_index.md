---
title: set_Rewind()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αυτό το χαρακτηριστικό καθορίζει αν το εφέ θα επαναφερθεί όταν ολοκληρωθεί η αναπαραγωγή. Γράψτε bool.
type: docs
weight: 326
url: /el/aspose.slides.animation/itiming/set_rewind/
---
## ITTiming::set_Rewind(bool) μέθοδος


Αυτό το χαρακτηριστικό καθορίζει αν το εφέ θα επαναφερθεί όταν ολοκληρωθεί η αναπαραγωγή. Γράψτε **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_Rewind(bool value)=0
```

## Παρατηρήσεις



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Get the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Turn the effect Timing/Rewind on.
effect->get_Timing()->set_Rewind(true);
```

## Δείτε επίσης

* Κλάση [ITiming](../)
* Χώρος ονομάτων [Aspose::Slides::Animation](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
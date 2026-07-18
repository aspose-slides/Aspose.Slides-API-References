---
title: get_Rewind()
second_title: Aspose.Slides για το API αναφοράς C++
description: Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επαναληφθεί όταν ολοκληρωθεί η αναπαραγωγή. Διαβάστε bool.
type: docs
weight: 313
url: /el/aspose.slides.animation/itiming/get_rewind/
---
## ITiming::get_Rewind() μέθοδος

Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επιστρέψει στην αρχή όταν ολοκληρωθεί η αναπαραγωγή. Διαβάστε **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_Rewind()=0
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
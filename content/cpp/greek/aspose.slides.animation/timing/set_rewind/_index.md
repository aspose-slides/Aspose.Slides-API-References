---
title: set_Rewind()
second_title: Aspose.Slides για C++ Αναφορά API
description: Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επανέλθει στην αρχή όταν ολοκληρωθεί η αναπαραγωγή. Γράψτε bool.
type: docs
weight: 248
url: /el/aspose.slides.animation/timing/set_rewind/
---
## Timing::set_Rewind(bool) μέθοδος

Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επανέλθει στην αρχή όταν ολοκληρωθεί η αναπαραγωγή. Γράψτε **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_Rewind(bool value) override
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

* Κλάση [Timing](../)
* Χώρος ονομάτων [Aspose::Slides::Animation](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
---
title: get_Rewind()
second_title: Aspose.Slides για C++ API Reference
description: Αυτή η ιδιότητα καθορίζει εάν το εφέ θα επανέλθει όταν ολοκληρωθεί η αναπαραγωγή. Ανάγνωση bool.
type: docs
weight: 235
url: /el/aspose.slides.animation/timing/get_rewind/
---
## Timing::get_Rewind() μέθοδος

Αυτή η ιδιότητα καθορίζει εάν το εφέ θα επανέλθει όταν ολοκληρωθεί η αναπαραγωγή. Ανάγνωση **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_Rewind() override
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
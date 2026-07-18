---
title: get_RepeatUntilNextClick()
second_title: Aspose.Slides για την αναφορά API C++
description: Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επαναλαμβάνεται μέχρι το επόμενο κλικ. Ανάγνωση bool.
type: docs
weight: 157
url: /el/aspose.slides.animation/timing/get_repeatuntilnextclick/
---
## Timing::get_RepeatUntilNextClick() μέθοδος


Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επαναλαμβάνεται μέχρι το επόμενο κλικ. Ανάγνωση **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_RepeatUntilNextClick() override
```

## Παρατηρήσεις



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## Δείτε επίσης

* Κλάση [Timing](../)
* Χώρος ονομάτων [Aspose::Slides::Animation](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
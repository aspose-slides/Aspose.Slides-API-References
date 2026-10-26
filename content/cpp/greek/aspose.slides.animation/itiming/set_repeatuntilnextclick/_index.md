---
title: set_RepeatUntilNextClick()
second_title: Aspose.Slides για την αναφορά API του C++
description: Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επαναληφθεί μέχρι το επόμενο κλικ. Γράψτε bool.
type: docs
weight: 170
url: /el/aspose.slides.animation/itiming/set_repeatuntilnextclick/
---
## ITiming::set_RepeatUntilNextClick(bool) μέθοδος


Αυτό το χαρακτηριστικό καθορίζει εάν το εφέ θα επαναληφθεί μέχρι το επόμενο κλικ. Γράψτε **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_RepeatUntilNextClick(bool value)=0
```

## Σχόλια



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

* Κλάση [ITiming](../)
* Χώρος ονομάτων [Aspose::Slides::Animation](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
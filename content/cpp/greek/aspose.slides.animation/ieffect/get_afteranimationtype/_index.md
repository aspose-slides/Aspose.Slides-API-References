---
title: get_AfterAnimationType()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ορίστηκε ένας τύπος μετά την κίνηση για το εφέ. Διαβάστε AfterAnimationType.
type: docs
weight: 222
url: /el/aspose.slides.animation/ieffect/get_afteranimationtype/
---
## IEffect::get_AfterAnimationType() μέθοδος


Ορίζεται ένας τύπος μετά την κίνηση για το εφέ. Διαβάστε [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::IEffect::get_AfterAnimationType()=0
```

## Παρατηρήσεις



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Λάβετε το πρώτο εφέ της πρώτης διαφάνειας.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Αλλάξτε το εφέ μετά την κίνηση σε "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Δείτε επίσης

* Απαρίθμηση [AfterAnimationType](../../afteranimationtype/)
* Κλάση [IEffect](../)
* Χώρος ονομάτων [Aspose::Slides::Animation](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
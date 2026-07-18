---
title: set_AfterAnimationType()
second_title: Αναφορά API Aspose.Slides για C++
description: Ορίζεται ένας τύπος μετά την κίνηση για το εφέ. Γράψτε AfterAnimationType.
type: docs
weight: 235
url: /el/aspose.slides.animation/ieffect/set_afteranimationtype/
---
## IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) μέθοδος

Ορίζεται ένας τύπος μετά την κίνηση για το εφέ. Γράψτε [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value)=0
```

## Παρατηρήσεις

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Λάβετε το πρώτο εφέ της πρώτης διαφάνειας.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Αλλάξτε το After animation του εφέ σε "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Δείτε επίσης

* Enum [AfterAnimationType](../../afteranimationtype/)
* Κλάση [IEffect](../)
* Χώρος ονομάτων [Aspose::Slides::Animation](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
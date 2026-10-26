---
title: get_AfterAnimationType()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ορίζει έναν τύπο μετά-ανίμασης για το εφέ. Διαβάστε AfterAnimationType.
type: docs
weight: 222
url: /el/aspose.slides.animation/effect/get_afteranimationtype/
---
## Effect::get_AfterAnimationType() μέθοδος


Ορίζει έναν τύπο μετά-ανίμασης για το effect. Διαβάστε [AfterAnimationType](../../afteranimationtype/).

```cpp
Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::Effect::get_AfterAnimationType() override
```

## Παρατηρήσεις



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Λάβετε το πρώτο εφέ της πρώτης διαφάνειας.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Αλλάξτε το εφέ After animation σε "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## Δείτε επίσης

* Enum [AfterAnimationType](../../afteranimationtype/)
* Κλάση [Effect](../)
* Χώρος ονομάτων [Aspose::Slides::Animation](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
---
title: set_AfterAnimationType()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ορίζει έναν τύπο μετά ανιματισμού για το εφέ. Γράψτε AfterAnimationType.
type: docs
weight: 235
url: /el/aspose.slides.animation/effect/set_afteranimationtype/
---
## Effect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) μέθοδος


Ορίζει έναν τύπο μετά ανιματισμού για το εφέ. Γράψτε [AfterAnimationType](../../afteranimationtype/).

```cpp
void Aspose::Slides::Animation::Effect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value) override
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

* Απαρίθμηση [AfterAnimationType](../../afteranimationtype/)
* Κλάση [Effect](../)
* Χώρος ονομάτων [Aspose::Slides::Animation](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
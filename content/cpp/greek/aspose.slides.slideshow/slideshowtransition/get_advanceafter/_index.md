---
title: get_AdvanceAfter()
second_title: Aspose.Slides για C++ Αναφορά API
description: Αυτό το χαρακτηριστικό καθορίζει εάν η παρουσίαση θα μεταβεί στην επόμενη διαφάνεια μετά από ορισμένο χρόνο. Ανάγνωση bool.
type: docs
weight: 105
url: /el/aspose.slides.slideshow/slideshowtransition/get_advanceafter/
---
## SlideShowTransition::get_AdvanceAfter() μέθοδος

Αυτό το χαρακτηριστικό καθορίζει εάν η παρουσίαση θα μεταβεί στην επόμενη διαφάνεια μετά από ορισμένο χρόνο. Ανάγνωση **bool**.

```cpp
bool Aspose::Slides::SlideShow::SlideShowTransition::get_AdvanceAfter() override
```

## Παρατηρήσεις


```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Λάβε την πρώτη μετάβαση διαφάνειας
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Έλεγξε αν η σημαία Advance Slide After είναι ενεργοποιημένη
if (slideTransition->get_AdvanceAfter())
{
    // Λάβε την τιμή του χρόνου Advance Slide After
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Δείτε επίσης

* Κλάση [SlideShowTransition](../)
* Χώρος ονομάτων [Aspose::Slides::SlideShow](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
---
title: set_AdvanceAfter()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αυτό το χαρακτηριστικό καθορίζει εάν η παρουσίαση θα μεταβεί στην επόμενη διαφάνεια μετά από κάποιο χρονικό διάστημα. Γράψτε bool.
type: docs
weight: 118
url: /el/aspose.slides.slideshow/slideshowtransition/set_advanceafter/
---
## SlideShowTransition::set_AdvanceAfter(bool) μέθοδος

Αυτό το χαρακτηριστικό καθορίζει εάν η παρουσίαση θα μετακινηθεί στην επόμενη διαφάνεια μετά από κάποιο χρόνο. Γράψτε **bool**.

```cpp
void Aspose::Slides::SlideShow::SlideShowTransition::set_AdvanceAfter(bool value) override
```

## Σχόλια

```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Λάβετε την πρώτη μετάβαση διαφάνειας
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Ελέγξτε αν η σημαία Advance Slide After είναι ενεργοποιημένη
if (slideTransition->get_AdvanceAfter())
{
    // Λάβετε την τιμή του Advance Slide After Time
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Δείτε επίσης

* Κλάση [SlideShowTransition](../)
* Χώρος ονομάτων [Aspose::Slides::SlideShow](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
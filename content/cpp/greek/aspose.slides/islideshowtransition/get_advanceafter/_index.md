---
title: get_AdvanceAfter()
second_title: Αναφορά API Aspose.Slides για C++
description: Αυτό το χαρακτηριστικό καθορίζει εάν η παρουσίαση θα μεταβεί στην επόμενη διαφάνεια μετά από κάποιο χρονικό διάστημα. Διαβάστε bool.
type: docs
weight: 105
url: /el/aspose.slides/islideshowtransition/get_advanceafter/
---
## ISlideShowTransition::get_AdvanceAfter() μέθοδος


Αυτό το χαρακτηριστικό καθορίζει εάν η παρουσίαση θα μεταβεί στην επόμενη διαφάνεια μετά από κάποιο χρονικό διάστημα. Διαβάστε **bool**.

```cpp
virtual bool Aspose::Slides::ISlideShowTransition::get_AdvanceAfter()=0
```

## Παρατηρήσεις



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Αποκτήστε την πρώτη μετάβαση διαφάνειας
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Ελέγξτε αν η σημαία Advance Slide After είναι ενεργοποιημένη
if (slideTransition->get_AdvanceAfter())
{
    // Λάβετε την τιμή του χρόνου Advance Slide After
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Δείτε επίσης

* Κλάση [ISlideShowTransition](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
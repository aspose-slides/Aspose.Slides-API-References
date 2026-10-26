---
title: set_AdvanceAfter()
second_title: Αναφορά API Aspose.Slides για C++
description: Αυτό το χαρακτηριστικό καθορίζει εάν η παρουσίαση θα μεταβεί στην επόμενη διαφάνεια μετά από κάποιο χρονικό διάστημα. Γράψτε bool.
type: docs
weight: 118
url: /el/aspose.slides/islideshowtransition/set_advanceafter/
---
## ISlideShowTransition::set_AdvanceAfter(bool) μέθοδος

Αυτό το χαρακτηριστικό καθορίζει εάν η παρουσίαση θα μεταβεί στην επόμενη διαφάνεια μετά από κάποιο χρονικό διάστημα. Γράψτε **bool**.

```cpp
virtual void Aspose::Slides::ISlideShowTransition::set_AdvanceAfter(bool value)=0
```

## Παρατηρήσεις

```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Λάβετε την πρώτη μετάβαση διαφάνειας
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Ελέγξτε αν η σημαία AdvanceAfter είναι ενεργοποιημένη
if (slideTransition->get_AdvanceAfter())
{
    // Λάβετε την τιμή χρόνου AdvanceAfter
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## Δείτε επίσης

* Κλάση [ISlideShowTransition](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
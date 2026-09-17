---
title: remove method
second_title: Αναφορά API Aspose.Slides για Python μέσω .NET
description: 
type: docs
url: /el/aspose.slides/layoutslidecollection/remove/
weight: 20
---
## remove(self, value) {#ilayoutslide}
Καταργεί μια διάταξη από τη συλλογή.

```python
def remove(self, value):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/el/aspose.slides/ilayoutslide) | Η διαφάση διάταξης που θα αφαιρεθεί από τη συλλογή. |

### Παρατηρήσεις

1) Για να αποφύγετε την εξαίρεση PptxEditException, ελέγξτε την ιδιότητα HasDependingSlides της διάταξης πριν.
2) Μπορείτε επίσης να χρησιμοποιήσετε τη μέθοδο [`ILayoutSlide.remove`](/slides/python-net/el/aspose.slides/ilayoutslide/remove) για να απλοποιήσετε τον κώδικα.

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| [`PptxEditException`](/slides/python-net/el/aspose.slides/pptxeditexception) | Εκκινείται εάν η διάταξη χρησιμοποιείται στην παρουσίαση (η ιδιότητα HasDependingSlides είναι true). |

### Δείτε επίσης
* κλάση [`ILayoutSlide`](/slides/python-net/el/aspose.slides/ilayoutslide)
* κλάση [`LayoutSlideCollection`](/slides/python-net/el/aspose.slides/layoutslidecollection)
* κλάση [`PptxEditException`](/slides/python-net/el/aspose.slides/pptxeditexception)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)
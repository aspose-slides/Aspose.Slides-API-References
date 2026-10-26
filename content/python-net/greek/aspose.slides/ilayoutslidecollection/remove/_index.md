---
title: remove method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/ilayoutslidecollection/remove/
weight: 20
---
## remove(self, value) {#ilayoutslide}
Αφαιρεί μια διάταξη από τη συλλογή.


```python
def remove(self, value):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/el/aspose.slides/ilayoutslide) | Η διάταξη διαφάνειας που θα αφαιρεθεί από τη συλλογή. |

### Παρατηρήσεις

1) Για να αποφύγετε την εξαίρεση PptxEditException, ελέγξτε πρώτα την ιδιότητα HasDependingSlides της διάταξης.
2) Μπορείτε επίσης να χρησιμοποιήσετε τη μέθοδο [`ILayoutSlide.remove`](/slides/python-net/el/aspose.slides/ilayoutslide/remove) για να απλοποιήσετε τον κώδικα.

### Εξαιρέσεις

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/el/aspose.slides/pptxeditexception) | Εμφανίζεται εάν η διάταξη χρησιμοποιείται στην παρουσίαση (η ιδιότητα HasDependingSlides είναι αληθής). |



### Δείτε επίσης
* κλάση [`ILayoutSlide`](/slides/python-net/el/aspose.slides/ilayoutslide)
* κλάση [`ILayoutSlideCollection`](/slides/python-net/el/aspose.slides/ilayoutslidecollection)
* κλάση [`PptxEditException`](/slides/python-net/el/aspose.slides/pptxeditexception)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)
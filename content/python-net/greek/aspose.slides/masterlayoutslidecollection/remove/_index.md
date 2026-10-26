---
title: remove method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/masterlayoutslidecollection/remove/
weight: 60
---
## remove(self, value) {#ilayoutslide}
Αφαιρεί μια διάταξη από τη συλλογή.

```python
def remove(self, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/el/aspose.slides/ilayoutslide) | Η διαφάνεια διάταξης που θα αφαιρεθεί από τη συλλογή. |

### Παρατηρήσεις

1) Για να αποφύγετε τη ρίψη του PptxEditException, ελέγξτε την ιδιότητα HasDependingSlides του layout πριν.  
2) Μπορείτε επίσης να χρησιμοποιήσετε τη μέθοδο [`ILayoutSlide.remove`](/slides/python-net/el/aspose.slides/ilayoutslide/remove) για να απλοποιήσετε τον κώδικα.

### Εξαιρέσεις

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/el/aspose.slides/pptxeditexception) | Εγείρεται αν η διάταξη χρησιμοποιείται στην παρουσίαση (η ιδιότητα HasDependingSlides είναι true). |

### Δείτε επίσης
* κατηγορία [`ILayoutSlide`](/slides/python-net/el/aspose.slides/ilayoutslide)
* κατηγορία [`MasterLayoutSlideCollection`](/slides/python-net/el/aspose.slides/masterlayoutslidecollection)
* κατηγορία [`PptxEditException`](/slides/python-net/el/aspose.slides/pptxeditexception)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)
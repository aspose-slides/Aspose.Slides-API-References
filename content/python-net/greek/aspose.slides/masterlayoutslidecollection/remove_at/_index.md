---
title: remove_at method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/masterlayoutslidecollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
Αφαιρεί το στοιχείο στο συγκεκριμένο δείκτη της συλλογής.


```python
def remove_at(self, index):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | **int** | Ο δείκτης μηδενικής βάσης του στοιχείου που θα αφαιρεθεί. |

### Παρατηρήσεις

1) Για να αποφύγετε την εξαίρεση PptxEditException, ελέγξτε την ιδιότητα HasDependingSlides του layout πριν.  
2) Μπορείτε επίσης να χρησιμοποιήσετε τη μέθοδο [`ILayoutSlide.remove`](/slides/python-net/el/aspose.slides/ilayoutslide/remove) για να απλοποιήσετε τον κώδικα.

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| [`PptxEditException`](/slides/python-net/el/aspose.slides/pptxeditexception) | Εκτοξεύεται εάν το layout χρησιμοποιείται στην παρουσίαση (η ιδιότητα HasDependingSlides είναι true). |



### Δείτε επίσης
* κλάση [`MasterLayoutSlideCollection`](/slides/python-net/el/aspose.slides/masterlayoutslidecollection)
* κλάση [`PptxEditException`](/slides/python-net/el/aspose.slides/pptxeditexception)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)
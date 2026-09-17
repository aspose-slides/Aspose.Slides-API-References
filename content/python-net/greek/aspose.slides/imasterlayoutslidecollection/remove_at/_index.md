---
title: remove_at method
second_title: Αναφορά API Aspose.Slides για Python μέσω .NET
description: 
type: docs
url: /el/aspose.slides/imasterlayoutslidecollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
Αφαιρεί το στοιχείο στο καθορισμένο δείκτη της συλλογής.

```python
def remove_at(self, index):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | **int** | Ο δεικτης που αρχίζει από το μηδέν του στοιχείου που πρέπει να αφαιρεθεί. |

### Παρατηρήσεις

1) Για να αποφευχθεί η ρίψη της PptxEditException, ελέγξτε την ιδιότητα HasDependingSlides του layout πριν.
2) Μπορείτε επίσης να χρησιμοποιήσετε τη μέθοδο [`ILayoutSlide.remove`](/slides/python-net/el/aspose.slides/ilayoutslide/remove) για να απλοποιήσετε τον κώδικα.

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| [`PptxEditException`](/slides/python-net/el/aspose.slides/pptxeditexception) | Εκτοπίζεται εάν το layout χρησιμοποιείται στην παρουσίαση (η ιδιότητα HasDependingSlides του είναι true). |

### Δείτε επίσης
* κλάση [`IMasterLayoutSlideCollection`](/slides/python-net/el/aspose.slides/imasterlayoutslidecollection)
* κλάση [`PptxEditException`](/slides/python-net/el/aspose.slides/pptxeditexception)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)
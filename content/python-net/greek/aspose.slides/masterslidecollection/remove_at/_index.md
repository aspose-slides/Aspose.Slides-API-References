---
title: remove_at method
second_title: Αναφορά API Aspose.Slides για Python μέσω .NET
description: 
type: docs
url: /el/aspose.slides/masterslidecollection/remove_at/
weight: 40
---
## remove_at(self, index) {#int}
Καταργεί το στοιχείο στον καθορισμένο δείκτη της συλλογής.


```python
def remove_at(self, index):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | **int** | Ο δείκτης με βάση το μηδέν του στοιχείου που θα αφαιρεθεί. |

### Παρατηρήσεις

Για να αποφύγετε την εξαίρεση PptxEditException, ελέγξτε πρώτα την ιδιότητα HasDependingSlides του master.

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| [`PptxEditException`](/slides/python-net/el/aspose.slides/pptxeditexception) | Εκτελείται εάν το master που αφαιρείται χρησιμοποιείται στην παρουσίαση (η ιδιότητα HasDependingSlides του είναι true). |

### Δείτε επίσης
* κλάση [`MasterSlideCollection`](/slides/python-net/el/aspose.slides/masterslidecollection)
* κλάση [`PptxEditException`](/slides/python-net/el/aspose.slides/pptxeditexception)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)
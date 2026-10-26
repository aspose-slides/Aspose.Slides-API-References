---
title: add_clone method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/masterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας διάταξης στο τέλος της συλλογής.

### Επιστρέφει

Διαφάνεια που προστέθηκε.



```python
def add_clone(self, source_layout):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/el/aspose.slides/ilayoutslide) | Διαφάνεια προς κλωνοποίηση. |

### Παρατηρήσεις

1) Η νέα διάταξη θα συνδεθεί με τη γονική κύρια διαφάνεια για αυτήν τη συλλογή διαφανειών διάταξης. Συνεπώς, αυτό είναι αντίστοιχο της εντολής Αντιγραφή/Επικόλληση με την επιλογή "Use Destination Theme" στο PowerPoint.
2) Το αντίστοιχο αυτής της μεθόδου είναι η μέθοδος **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** που προσπελάζεται μέσω της ιδιότητας [`IPresentation.layout_slides`](/slides/python-net/el/aspose.slides/ipresentation/layout_slides).

### Δείτε επίσης
* κλάση [`ILayoutSlide`](/slides/python-net/el/aspose.slides/ilayoutslide)
* κλάση [`MasterLayoutSlideCollection`](/slides/python-net/el/aspose.slides/masterlayoutslidecollection)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)
---
title: add_clone method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/imasterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας διάταξης στο τέλος της συλλογής.

### Επιστρέφει

Προστιθέμενη διαφάνεια.

```python
def add_clone(self, source_layout):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/el/aspose.slides/ilayoutslide) | Διαφάνεια προς κλωνοποίηση. |

### Παρατηρήσεις

1) Η νέα διάταξη θα συνδεθεί με τη γονική κύρια διαφάνεια για τη συλλογή διαφανειών αυτής της διάταξης.  
   Έτσι, αυτό είναι αλληλόμορφο της αντιγραφής/επικόλλησης με τη ρύθμιση "Use Destination Theme" στο PowerPoint.  
2) Αλληλόμορφο αυτής της μεθόδου είναι η μέθοδος **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** που προσπελαύνεται με την ιδιότητα [`IPresentation.layout_slides`](/slides/python-net/el/aspose.slides/ipresentation/layout_slides).

### Δείτε επίσης
* κλάση [`ILayoutSlide`](/slides/python-net/el/aspose.slides/ilayoutslide)
* κλάση [`IMasterLayoutSlideCollection`](/slides/python-net/el/aspose.slides/imasterlayoutslidecollection)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)
---
title: add_clone method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/globallayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας διάταξης στην παρουσίαση.

### Returns
Προστέθηκε διαφάνεια.

```python
def add_clone(self, source_layout):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/el/aspose.slides/ilayoutslide) | Διαφάνεια προς κλωνοποίηση. |

### Remarks
Κατά την κλωνοποίηση μιας διάταξης μεταξύ διαφορετικών παρουσιάσεων, ο master της διάταξης μπορεί επίσης να κλωνοποιηθεί για να διατηρηθεί η μορφοποίηση της πηγής.
Χρησιμοποιείται ένα εσωτερικό μητρώο για την παρακολούθηση των αυτόματα κλωνοποιημένων master ώστε να αποτραπεί η δημιουργία πολλαπλών κλώνων του ίδιου master slide.
Η χειροκίνητη κλωνοποίηση των master slides δεν θα αποτραπεί ούτε θα καταγραφεί.

## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας διάταξης στην παρουσίαση.

### Returns
Προστέθηκε διαφάνεια.

```python
def add_clone(self, source_layout, dest_master):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/el/aspose.slides/ilayoutslide) | Διαφάνεια προς κλωνοποίηση. |
| dest_master | [`IMasterSlide`](/slides/python-net/el/aspose.slides/imasterslide) | Master slide για μια νέα διάταξη. |

### Remarks
1) Η νέα διάταξη θα συνδεθεί με τον καθορισμένο master στην προορισμένη παρουσίαση.
            Επομένως αυτό είναι το ανάλογο της αντιγραφής/επικόλλησης με την επιλογή "Use Destination Theme" στο PowerPoint.
2) Το ανάλογο αυτής της μεθόδου είναι η μέθοδος **Aspose.Slides.IMasterLayoutSlideCollection.AddClone(Aspose.Slide**
            προσπελάζεται μέσω της ιδιότητας [`IMasterSlide.layout_slides`](/slides/python-net/el/aspose.slides/imasterslide/layout_slides).

### See Also
* κλάση [`GlobalLayoutSlideCollection`](/slides/python-net/el/aspose.slides/globallayoutslidecollection)
* κλάση [`ILayoutSlide`](/slides/python-net/el/aspose.slides/ilayoutslide)
* κλάση [`IMasterSlide`](/slides/python-net/el/aspose.slides/imasterslide)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)
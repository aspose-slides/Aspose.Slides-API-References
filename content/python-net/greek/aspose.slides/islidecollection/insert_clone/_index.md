---
title: insert_clone method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/islidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
Εισάγει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στη συγκεκριμένη θέση της συλλογής.

### Returns
Διαφάνεια που εισήχθη.

```python
def insert_clone(self, index, source_slide):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Δείκτης της νέας διαφάνειας. |
| source_slide | [`ISlide`](/slides/python-net/el/aspose.slides/islide) | Διαφάνεια προς κλωνοποίηση. |

### Remarks
Κατά την κλωνοποίηση μιας διαφάνειας μεταξύ διαφορετικών παρουσιάσεων, η κύρια διαφάνεια μπορεί επίσης να κλωνοποιηθεί.
Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide.
Manual cloning of master slides will be neither prevented nor registered.
If you need more control over cloning process use
**Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** or
**Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** for cloning slides and
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** for cloning masters.

## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
Εισάγει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στη συγκεκριμένη θέση της συλλογής.

### Returns
Διαφάνεια που εισήχθη.

```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Δείκτης της νέας διαφάνειας. |
| source_slide | [`ISlide`](/slides/python-net/el/aspose.slides/islide) | Διαφάνεια προς κλωνοποίηση. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/el/aspose.slides/ilayoutslide) | Διαφάνεια διάταξης για μια νέα διαφάνεια. |

## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
Εισάγει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας προέλευσης στη συγκεκριμένη θέση της συλλογής.
Κατάλληλη διάταξη θα επιλεγεί αυτόματα από το καθορισμένο κύριο (κατάλληλη διάταξη είναι η διάταξη με τον ίδιο Type ή Name όπως η διάταξη της διαφάνειας προέλευσης). Εάν δεν υπάρχει κατάλληλη διάταξη, η διάταξη της διαφάνειας προέλευσης θα κλωνοποιηθεί (αν το allowCloneMissingLayout είναι true) ή θα εξαπολυθεί PptxEditException (αν το allowCloneMissingLayout είναι false).

### Returns
Διαφάνεια που εισήχθη.

```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Δείκτης της νέας διαφάνειας. |
| source_slide | [`ISlide`](/slides/python-net/el/aspose.slides/islide) | Διαφάνεια προς κλωνοποίηση. |
| dest_master | [`IMasterSlide`](/slides/python-net/el/aspose.slides/imasterslide) | Κύρια διαφάνεια για μια νέα διαφάνεια. |
| allow_clone_missing_layout | **bool** | Εάν δεν υπάρχει κατάλληλη διάταξη στον καθορισμένο κύριο, τότε η διάταξη της <br/><br/> διαφάνειας προέλευσης θα κλωνοποιηθεί (αν το allowCloneMissingLayout είναι true) ή <br/><br/> θα εξαπολυθεί PptxEditException (αν το allowCloneMissingLayout είναι false). |

### Exceptions

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/el/aspose.slides/pptxeditexception) | Εκρεμεί εάν δεν υπάρχει κατάλληλη διάταξη στον καθορισμένο κύριο και <br/>            το allowCloneMissingLayout είναι false. |

### See Also
* κλάση [`ILayoutSlide`](/slides/python-net/el/aspose.slides/ilayoutslide)
* κλάση [`IMasterSlide`](/slides/python-net/el/aspose.slides/imasterslide)
* κλάση [`ISlide`](/slides/python-net/el/aspose.slides/islide)
* κλάση [`ISlideCollection`](/slides/python-net/el/aspose.slides/islidecollection)
* κλάση [`PptxEditException`](/slides/python-net/el/aspose.slides/pptxeditexception)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)
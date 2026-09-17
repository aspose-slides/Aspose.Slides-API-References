---
title: add_clone method
second_title: Αναφορά API Aspose.Slides για Python μέσω .NET
description: 
type: docs
url: /el/aspose.slides/islidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
Προσθέτει ένα αντίγραφό μιας καθορισμένης διαφάνειας στο τέλος της συλλογής.

### Επιστρέφει

Νέα διαφάνεια.



```python
def add_clone(self, source_slide):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/el/aspose.slides/islide) | Διαφάνεια προς κλωνοποίηση. |

### Παρατηρήσεις

When cloning a slide between different presentations slide's master can be cloned too.
            Internal registry is used to track automatically cloned masters to prevent creation of 
            multiple clones of the same master slide.
            Manual cloning of master slides will be neither prevented nor registered.
            If you need more control over cloning process use
            **Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** or
            **Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** for cloning slides,
            **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** or
            **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** for cloning layouts and
            **Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** for cloning masters.


## add_clone(self, source_slide, section) {#islide-isection}
Προσθέτει ένα αντίγραφό μιας καθορισμένης διαφάνειας στο τέλος της καθορισμένης ενότητας.

### Επιστρέφει

Νέα διαφάνεια.



```python
def add_clone(self, source_slide, section):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/el/aspose.slides/islide) | Διαφάνεια προς κλωνοποίηση. |
| section | [`ISection`](/slides/python-net/el/aspose.slides/isection) | Ενότητα για νέα διαφάνεια. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/el/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
Προσθέτει ένα αντίγραφό μιας καθορισμένης διαφάνειας στο τέλος της συλλογής.

### Επιστρέφει

Νέα διαφάνεια.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/el/aspose.slides/islide) | Διαφάνεια προς κλωνοποίηση. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/el/aspose.slides/ilayoutslide) | Διαφάνεια διάταξης για νέα διαφάνεια. |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
Προσθέτει ένα αντίγραφό μιας καθορισμένης διαφάνειας προέλευσης στο τέλος της συλλογής.
            Appropriate layout will be selected automatically from the specified 
            master (appropriate layout is the layout with the same Type or Name as 
            of layout of the source slide). If there is no appropriate layout then
            layout of the source slide will be cloned (if allowCloneMissingLayout 
            is true) or PptxEditException will be thrown (if allowCloneMissingLayout
            is false).

### Επιστρέφει

Νέα διαφάνεια.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/el/aspose.slides/islide) | Διαφάνεια προς κλωνοποίηση. |
| dest_master | [`IMasterSlide`](/slides/python-net/el/aspose.slides/imasterslide) | Master slide for a new slide. |
| allow_clone_missing_layout | **bool** | Εάν δεν υπάρχει κατάλληλη διάταξη στον καθορισμένο master, τότε η διάταξη της <br/><br/>            source slide θα κλωνοποιηθεί (εάν το allowCloneMissingLayout είναι αληθές) ή <br/><br/>            PptxEditException θα ριχθεί (εάν το allowCloneMissingLayout είναι ψευδές). |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| [`PptxEditException`](/slides/python-net/el/aspose.slides/pptxeditexception) | Γίνεται ρίψη εάν δεν υπάρχει κατάλληλη διάταξη στον καθορισμένο master και <br/>            allowCloneMissingLayout είναι ψευδές. |



### Δείτε επίσης
* κλάση [`ILayoutSlide`](/slides/python-net/el/aspose.slides/ilayoutslide)
* κλάση [`IMasterSlide`](/slides/python-net/el/aspose.slides/imasterslide)
* κλάση [`ISection`](/slides/python-net/el/aspose.slides/isection)
* κλάση [`ISlide`](/slides/python-net/el/aspose.slides/islide)
* κλάση [`ISlideCollection`](/slides/python-net/el/aspose.slides/islidecollection)
* κλάση [`PptxEditException`](/slides/python-net/el/aspose.slides/pptxeditexception)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)
---
title: add_clone method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/slidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας στο τέλος της συλλογής.

### Returns

Νέα διαφάνεια.



```python
def add_clone(self, source_slide):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/el/aspose.slides/islide) | Διαφάνεια προς κλωνοποίηση. |

### Remarks

Όταν κλωνοποιείται μια διαφάνεια μεταξύ διαφορετικών παρουσιάσεων, μπορεί να κλωνοποιηθεί και το master της διαφάνειας.
Η εσωτερική καταχώρηση χρησιμοποιείται για την παρακολούθηση αυτόματα κλωνοποιημένων master, ώστε να αποτραπεί η δημιουργία
πολλαπλών κλωνών του ίδιου master slide.
Η χειροκίνητη κλωνοποίηση των master slides δεν θα αποτραπεί ούτε θα καταγραφεί.
Αν χρειάζεστε μεγαλύτερο έλεγχο της διαδικασίας κλωνοποίησης, χρησιμοποιήστε
**Aspose.Slides.SlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** ή
**Aspose.Slides.SlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** για κλωνοποίηση διαφανειών,
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** ή
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** για κλωνοποίηση διατάξεων και
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** για κλωνοποίηση master.


## add_clone(self, source_slide, section) {#islide-isection}
Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας στο τέλος της καθορισμένης ενότητας.

### Returns

Νέα διαφάνεια.



```python
def add_clone(self, source_slide, section):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/el/aspose.slides/islide) | Διαφάνεια προς κλωνοποίηση. |
| section | [`ISection`](/slides/python-net/el/aspose.slides/isection) | Ενότητα για τη νέα διαφάνεια. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/el/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας στο τέλος της συλλογής.

### Returns

Νέα διαφάνεια.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/el/aspose.slides/islide) | Διαφάνεια προς κλωνοποίηση. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/el/aspose.slides/ilayoutslide) | Διάταξη διαφάνειας για τη νέα διαφάνεια. |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
Προσθέτει ένα αντίγραφο μιας καθορισμένης πηγής διαφάνειας στο τέλος της συλλογής.
            Το κατάλληλο layout θα επιλεγεί αυτόματα από το καθορισμένο 
            master (το κατάλληλο layout είναι το layout με τον ίδιο Type ή Name όπως 
            το layout της πηγής διαφάνειας). Εάν δεν υπάρχει κατάλληλο layout,
            το layout της πηγής διαφάνειας θα κλωνοποιηθεί (εάν το allowCloneMissingLayout 
            είναι true) ή θα εξαχθεί PptxEditException (εάν το allowCloneMissingLayout
            είναι false).

### Returns

Νέα διαφάνεια.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/el/aspose.slides/islide) | Διαφάνεια προς κλωνοποίηση. |
| dest_master | [`IMasterSlide`](/slides/python-net/el/aspose.slides/imasterslide) | Master slide για τη νέα διαφάνεια. |
| allow_clone_missing_layout | **bool** | Εάν δεν υπάρχει κατάλληλο layout στον καθορισμένο master, τότε το layout της <br/><br/>            πηγής διαφάνειας θα κλωνοποιηθεί (εάν το allowCloneMissingLayout είναι true) ή <br/><br/>            θα εξαχθεί PptxEditException (εάν το allowCloneMissingLayout είναι false). |

### Exceptions

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/el/aspose.slides/pptxeditexception) | Εκρίεται εάν δεν υπάρχει κατάλληλο layout στον καθορισμένο master και το allowCloneMissingLayout είναι false. |



### See Also
* κλάση [`ILayoutSlide`](/slides/python-net/el/aspose.slides/ilayoutslide)
* κλάση [`IMasterSlide`](/slides/python-net/el/aspose.slides/imasterslide)
* κλάση [`ISection`](/slides/python-net/el/aspose.slides/isection)
* κλάση [`ISlide`](/slides/python-net/el/aspose.slides/islide)
* κλάση [`PptxEditException`](/slides/python-net/el/aspose.slides/pptxeditexception)
* κλάση [`SlideCollection`](/slides/python-net/el/aspose.slides/slidecollection)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)
---
title: add_clone method
second_title: Αναφορά API Aspose.Slides για Python μέσω .NET
description: 
type: docs
url: /el/aspose.slides/igloballayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας διάταξης στην παρουσίαση.

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

Κατά την κλωνοποίηση μιας διάταξης μεταξύ διαφορετικών παρουσιάσεων, ο κύριος της διάταξης μπορεί επίσης να κλωνοποιηθεί
            για να διατηρηθεί η μορφοποίηση προέλευσης.
            Το εσωτερικό μητρώο χρησιμοποιείται για την παρακολούθηση αυτόματα κλωνοποιημένων κυρίων, ώστε να αποτραπεί η δημιουργία 
            πολλαπλών κλώνων της ίδιας κύριας διαφάνειας.
            Η χειροκίνητη κλωνοποίηση κυρίων διαφανειών δεν θα αποτραπεί ούτε θα καταγραφεί.


## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας διάταξης στην παρουσίαση.

### Επιστρέφει

Διαφάνεια που προστέθηκε.



```python
def add_clone(self, source_layout, dest_master):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/el/aspose.slides/ilayoutslide) | Διαφάνεια προς κλωνοποίηση. |
| dest_master | [`IMasterSlide`](/slides/python-net/el/aspose.slides/imasterslide) | Κύρια διαφάνεια για νέα διάταξη. |

### Παρατηρήσεις

Η νέα διάταξη θα συνδεθεί με τον καθορισμένο κύριο στην παρουσίαση προορισμού.
            Έτσι, αυτό είναι το αντίστοιχο της αντιγραφής/επικόλλησης με την επιλογή "Use Destination Theme" στο PowerPoint.



### Δείτε επίσης
* κλάση [`IGlobalLayoutSlideCollection`](/slides/python-net/el/aspose.slides/igloballayoutslidecollection)
* κλάση [`ILayoutSlide`](/slides/python-net/el/aspose.slides/ilayoutslide)
* κλάση [`IMasterSlide`](/slides/python-net/el/aspose.slides/imasterslide)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)
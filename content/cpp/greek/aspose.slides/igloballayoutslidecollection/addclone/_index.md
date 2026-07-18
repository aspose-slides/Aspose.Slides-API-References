---
title: AddClone()
second_title: Aspose.Slides για C++ API Αναφορά
description: Προσθέτει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας διάταξης στην παρουσίαση.
type: docs
weight: 1
url: /el/aspose.slides/igloballayoutslidecollection/addclone/
---
## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) μέθοδος

Προσθέτει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας διάταξης στην παρουσίαση.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) για κλωνοποίηση. |

### Τιμή Επιστροφής

Διαφάνεια που προστέθηκε.

## Παρατηρήσεις

Κατά την κλωνοποίηση μιας διάταξης μεταξύ διαφορετικών παρουσιάσεων, ο master της διάταξης μπορεί επίσης να κλωνοποιηθεί για να διατηρηθεί η μορφοποίηση προέλευσης. Χρησιμοποιείται εσωτερικό μητρώο για την παρακολούθηση αυτόματα κλωνοποιημένων master ώστε να αποτραπεί η δημιουργία πολλαπλών κλώνων του ίδιου master slide. Η χειροκίνητη κλωνοποίηση των master slide δεν θα αποτραπεί ούτε θα καταγραφεί.

## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) μέθοδος

Προσθέτει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας διάταξης στην παρουσίαση.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) για κλωνοποίηση. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Master slide για νέα διάταξη. |

### Τιμή Επιστροφής

Διαφάνεια που προστέθηκε.

## Παρατηρήσεις

Η νέα διάταξη θα συνδεθεί με τον καθορισμένο master στην παρουσίαση προορισμού. Έτσι, αυτό είναι ανάλογο με την αντιγραφή/επικόλληση με την επιλογή "Use Destination Theme" στο PowerPoint.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IGlobalLayoutSlideCollection](../)
* Class [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
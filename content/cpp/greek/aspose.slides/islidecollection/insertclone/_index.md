---
title: InsertClone()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Εισάγει ένα αντίγραφο μιας καθορισμένης διαφάνειας στη συγκεκριμένη θέση της συλλογής.
type: docs
weight: 27
url: /el/aspose.slides/islidecollection/insertclone/
---
## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) μέθοδος

Εισάγει ένα αντίγραφο μιας καθορισμένης διαφάνειας στη συγκεκριμένη θέση της συλλογής.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Δείκτης της νέας διαφάνειας. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) για κλωνοποίηση. |

### Τιμή Επιστροφής

Διαφάνεια που εισήχθη.

## Παρατηρήσεις

Κατά την κλωνοποίηση μιας διαφάνειας μεταξύ διαφορετικών παρουσιάσεων, ο κύριος της διαφάνειας μπορεί επίσης να κλωνοποιηθεί. Ένα εσωτερικό μητρώο χρησιμοποιείται για την παρακολούθηση αυτόματα κλωνοποιημένων κυρίων ώστε να αποτραπεί η δημιουργία πολλαπλών κλώνων του ίδιου κύριου διαφάνειας. Η χειροκίνητη κλωνοποίηση των κύριων διαφανειών δεν θα αποτραπεί ούτε θα καταγραφεί. Εάν χρειάζεστε μεγαλύτερο έλεγχο της διαδικασίας κλωνοποίησης, χρησιμοποιήστε [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) ή [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) για κλωνοποίηση διαφανειών και [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) για κλωνοποίηση κυρίων.

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) μέθοδος

Εισάγει ένα αντίγραφο μιας καθορισμένης διαφάνειας στη συγκεκριμένη θέση της συλλογής.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Δείκτης της νέας διαφάνειας. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) για κλωνοποίηση. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Διάταξη διαφάνειας για μια νέα διαφάνεια. |

### Τιμή Επιστροφής

Διαφάνεια που εισήχθη.

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) μέθοδος

Εισάγει ένα αντίγραφο μιας καθορισμένης πηγαίας διαφάνειας στη συγκεκριμένη θέση της συλλογής. Η κατάλληλη διάταξη θα επιλεγεί αυτόματα από τον καθορισμένο κύριο (η κατάλληλη διάταξη είναι η διάταξη με τον ίδιο Τύπο ή Όνομα όπως η διάταξη της πηγαίας διαφάνειας). Εάν δεν υπάρχει κατάλληλη διάταξη, τότε η διάταξη της πηγαίας διαφάνειας θα κλωνοποιηθεί (αν allowCloneMissingLayout είναι true) ή θα εξαπολυθεί η PptxEditException (αν allowCloneMissingLayout είναι false).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Δείκτης της νέας διαφάνειας. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) για κλωνοποίηση. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Κύρια διαφάνεια για μια νέα διαφάνεια. |
| allowCloneMissingLayout | **bool** | Εάν δεν υπάρχει κατάλληλη διάταξη στον καθορισμένο κύριο, τότε η διάταξη της πηγαίας διαφάνειας θα κλωνοποιηθεί (αν allowCloneMissingLayout είναι true) ή θα εξαπολυθεί η PptxEditException (αν allowCloneMissingLayout είναι false). |

### Τιμή Επιστροφής

Διαφάνεια που εισήχθη.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISlide](../../islide/)
* Κλάση [ISlideCollection](../)
* Κλάση [ILayoutSlide](../../ilayoutslide/)
* Κλάση [IMasterSlide](../../imasterslide/)
* Χώρος Ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
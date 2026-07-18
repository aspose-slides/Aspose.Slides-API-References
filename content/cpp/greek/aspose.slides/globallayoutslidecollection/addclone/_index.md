---
title: AddClone()
second_title: Αναφορά API του Aspose.Slides για C++
description: Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας διάταξης στην παρουσίαση.
type: docs
weight: 1
url: /el/aspose.slides/globallayoutslidecollection/addclone/
---
## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) μέθοδος

Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας διάταξης στην παρουσίαση.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### Παραμέτροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) για κλωνοποίηση. |

### Τιμή Επιστροφής

Διαφάνεια που προστέθηκε.

## Παρατηρήσεις

Κατά την κλωνοποίηση μιας διάταξης μεταξύ διαφορετικών παρουσιάσεων, ο κύριος (master) της διάταξης μπορεί επίσης να κλωνοποιηθεί ώστε να διατηρηθεί η μορφοποίηση της πηγής. Χρησιμοποιείται εσωτερικό μητρώο για την παρακολούθηση των αυτόματα κλωνοποιημένων κύριων, ώστε να αποτραπεί η δημιουργία πολλαπλών κλώνων του ίδιου κύριου διαφάνειας. Η χειροκίνητη κλωνοποίηση των κύριων διαφάνειων δεν θα εμποδιστεί ούτε θα καταγραφεί.

## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) μέθοδος

Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας διάταξης στην παρουσίαση.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster) override
```

### Παραμέτροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) για κλωνοποίηση. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Κύρια διαφάνεια για μια νέα διάταξη. |

### Τιμή Επιστροφής

Διαφάνεια που προστέθηκε.

## Παρατηρήσεις

1) Η νέα διάταξη θα συνδεθεί με τον ορισμένο κύριο στην προοριστική παρουσίαση. Έτσι είναι το ανάλογο της αντιγραφής/επικόλλησης με την επιλογή "Use Destination Theme" στο PowerPoint. 2) Το ανάλογο αυτής της μεθόδου είναι η μέθοδος [IMasterLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../imasterlayoutslidecollection/addclone/) που προσπελάζεται με την ιδιότητα [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/).

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ILayoutSlide](../../ilayoutslide/)
* Κλάση [GlobalLayoutSlideCollection](../)
* Κλάση [IMasterSlide](../../imasterslide/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
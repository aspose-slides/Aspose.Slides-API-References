---
title: InsertClone()
second_title: Aspose.Slides για C++ Αναφορά API
description: Εισάγει ένα αντίγραφο μιας καθορισμένης διαφάνειας διάταξης στη συγκεκριμένη θέση της συλλογής.
type: docs
weight: 14
url: /el/aspose.slides/imasterlayoutslidecollection/insertclone/
---
## IMasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) μέθοδος

Εισάγει ένα αντίγραφο μιας καθορισμένης διαφάνειας διάταξης στη συγκεκριμένη θέση της συλλογής.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Δείκτης της νέας διαφάνειας. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) για κλωνοποίηση. |

### Τιμή Επιστροφής

Η εισαχθείσα διαφάνεια.

## Παρατηρήσεις

Η νέα διάταξη θα συνδεθεί με τη γονική κύρια διαφάνεια για αυτή τη συλλογή διαφανειών διάταξης. Έτσι είναι αντίστοιχο της λειτουργίας αντιγραφής/επικόλλησης με την επιλογή "Use Destination Theme" στο PowerPoint.

## Δείτε επίσης

* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [ILayoutSlide](../../ilayoutslide/)
* Κλάση [IMasterLayoutSlideCollection](../)
* Ονοματοχώρος [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
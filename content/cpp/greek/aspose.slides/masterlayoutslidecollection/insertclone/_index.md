---
title: InsertClone()
second_title: Aspose.Slides για C++ API Αναφορά
description: Εισάγει ένα αντίγραφο μιας καθορισμένης διαφάνειας διάταξης στη καθορισμένη θέση της συλλογής.
type: docs
weight: 14
url: /el/aspose.slides/masterlayoutslidecollection/insertclone/
---
## MasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) μέθοδος

Εισάγει ένα αντίγραφο μιας καθορισμένης διαφάνειας διάταξης στη καθορισμένη θέση της συλλογής.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Δείκτης της νέας διαφάνειας. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) για κλωνοποίηση. |

### Τιμή Επιστροφής

Εισαχθείσα διαφάνεια.

## Παρατηρήσεις

Η νέα διάταξη θα συνδεθεί με τη γονική κύρια διαφάνεια για αυτή τη συλλογή διαφανειών διάταξης. Έτσι είναι ισοδύναμη με αντιγραφή/επικόλληση με την επιλογή \"Use Destination Theme\" στο PowerPoint. 

## Δείτε Επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ILayoutSlide](../../ilayoutslide/)
* Κλάση [MasterLayoutSlideCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
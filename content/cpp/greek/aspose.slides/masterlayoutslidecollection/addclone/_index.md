---
title: AddClone()
second_title: Aspose.Slides για την Αναφορά API του C++
description: Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας διάταξης στο τέλος της συλλογής.
type: docs
weight: 1
url: /el/aspose.slides/masterlayoutslidecollection/addclone/
---
## MasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) μέθοδος

Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας διάταξης στο τέλος της συλλογής.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) για κλωνοποίηση. |

### Τιμή επιστροφής

Προτέθηκε διαφάνεια.

## Παρατηρήσεις

1) Η νέα διάταξη θα συνδεθεί με τη γονική κύρια διαφάνεια για αυτή τη συλλογή διαφανειών διάταξης. Έτσι είναι ανάλογο της αντιγραφής/επικόλλησης με την επιλογή \"Use Destination Theme\" στο PowerPoint. 2) Αντίστοιχο αυτής της μεθόδου είναι η μέθοδος [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) που προσπελάζεται με την ιδιότητα [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/). 

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ILayoutSlide](../../ilayoutslide/)
* Κλάση [MasterLayoutSlideCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
---
title: AddClone()
second_title: Aspose.Slides για C++ API Αναφορά
description: Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας διάταξης στο τέλος της συλλογής.
type: docs
weight: 1
url: /el/aspose.slides/imasterlayoutslidecollection/addclone/
---
## IMasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) μέθοδος

Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας διάταξης στο τέλος της συλλογής.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) για κλωνοποίηση. |

### Τιμή Επιστροφής

Προστέθηκε διαφάνεια.

## Σχόλια

1) Η νέα διάταξη θα συνδεθεί με τη γονική κύρια διαφάνεια για αυτήν τη συλλογή διαφανειών διάταξης. Έτσι, αυτό είναι αντίστοιχο της αντιγραφής/επικόλλησης με την επιλογή "Use Destination Theme" στο PowerPoint. 2) Το αντίστοιχο αυτής της μεθόδου είναι η μέθοδος [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) η οποία προσπερνάται με την ιδιότητα [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/).

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ILayoutSlide](../../ilayoutslide/)
* Κλάση [IMasterLayoutSlideCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
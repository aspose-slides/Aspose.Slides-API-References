---
title: AddClone()
second_title: Aspose.Slides για C++ Αναφορά API
description: Προσθέτει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στο τέλος της συλλογής.
type: docs
weight: 14
url: /el/aspose.slides/islidecollection/addclone/
---
## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>) μέθοδος

Προσθέτει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στο τέλος της συλλογής.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) για κλωνοποίηση. |

### Τιμή Επιστροφής

Νέα διαφάνεια.

## Παρατηρήσεις

Κατά την κλωνοποίηση μιας διαφάνειας μεταξύ διαφορετικών παρουσιάσεων, το master της διαφάνειας μπορεί επίσης να κλωνοποιηθεί. Χρησιμοποιείται εσωτερικό μητρώο για την παρακολούθηση αυτόματης κλωνοποίησης των masters, ώστε να αποτραπεί η δημιουργία πολλαπλών κλώνων του ίδιου master διαφάνειας. Η χειροκίνητη κλωνοποίηση των master διαφανειών δεν θα αποτραπεί ούτε θα καταγραφεί. Εάν χρειάζεστε μεγαλύτερο έλεγχο της διαδικασίας κλωνοποίησης, χρησιμοποιήστε [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) ή [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) για κλωνοποίηση διαφανειών, [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) ή [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) για κλωνοποίηση διατάξεων και [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) για κλωνοποίηση masters.

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) μέθοδος

Προσθέτει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στο τέλος της συγκεκριμένης ενότητας.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) για κλωνοποίηση. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) για μια νέα διαφάνεια. |

### Τιμή Επιστροφής

Νέα διαφάνεια.

## Παρατηρήσεις

```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 50.0f, 300.0f, 100.0f);
presentation->get_Sections()->AddSection(u"Section 1", presentation->get_Slides()->idx_get(0));
auto section2 = presentation->get_Sections()->AppendEmptySection(u"Section 2");
presentation->get_Slides()->AddClone(presentation->get_Slides()->idx_get(0), section2);
// Τώρα η δεύτερη ενότητα περιέχει ένα αντίγραφο της πρώτης διαφάνειας.
```

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) μέθοδος

Προσθέτει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στο τέλος της συλλογής.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) για κλωνοποίηση. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Διαφάνεια διάταξης για μια νέα διαφάνεια. |

### Τιμή Επιστροφής

Νέα διαφάνεια.

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) μέθοδος

Προσθέτει ένα αντίγραφο μιας συγκεκριμένης πηγαίας διαφάνειας στο τέλος της συλλογής. Η κατάλληλη διάταξη θα επιλεγεί αυτόματα από το καθορισμένο master (η κατάλληλη διάταξη είναι η διάταξη με τον ίδιο τύπο ή όνομα όπως η διάταξη της πηγαίας διαφάνειας). Εάν δεν υπάρχει κατάλληλη διάταξη στο καθορισμένο master, τότε η διάταξη της πηγαίας διαφάνειας θα κλωνοποιηθεί (εάν το allowCloneMissingLayout είναι true) ή θα προκληθεί PptxEditException (εάν το allowCloneMissingLayout είναι false).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) για κλωνοποίηση. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Κύρια διαφάνεια για μια νέα διαφάνεια. |
| allowCloneMissingLayout | **bool** | Εάν δεν υπάρχει κατάλληλη διάταξη στο καθορισμένο master, τότε η διάταξη της πηγαίας διαφάνειας θα κλωνοποιηθεί (εάν το allowCloneMissingLayout είναι true) ή θα προκληθεί PptxEditException (εάν το allowCloneMissingLayout είναι false). |

### Τιμή Επιστροφής

Νέα διαφάνεια.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISlide](../../islide/)
* Κλάση [ISlideCollection](../)
* Κλάση [ISection](../../isection/)
* Κλάση [ILayoutSlide](../../ilayoutslide/)
* Κλάση [IMasterSlide](../../imasterslide/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
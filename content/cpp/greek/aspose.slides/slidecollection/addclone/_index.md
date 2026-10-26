---
title: AddClone()
second_title: Aspose.Slides για C++ API Αναφορά
description: Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας στο τέλος της συλλογής.
type: docs
weight: 53
url: /el/aspose.slides/slidecollection/addclone/
---
## SlideCollection::AddClone(System::SharedPtr\<ISlide\>) μέθοδος


Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας στο τέλος της συλλογής.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide) override
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) για κλωνοποίηση. |

### Τιμή Επιστροφής

Νέα διαφάνεια.
## Σχόλια



Κατά την κλωνοποίηση μιας διαφάνειας μεταξύ διαφορετικών παρουσιάσεων, το master της διαφάνειας μπορεί επίσης να κλωνοποιηθεί. Χρησιμοποιείται εσωτερικό μητρώο για την παρακολούθηση των αυτόματα κλωνοποιημένων master ώστε να αποτραπεί η δημιουργία πολλαπλών κλώνων του ίδιου master διαφάνειας. Η χειροκίνητη κλωνοποίηση των master διαφανειών δεν θα αποτραπεί ούτε θα καταγραφεί. Εάν χρειάζεστε μεγαλύτερο έλεγχο στη διαδικασία κλωνοποίησης, χρησιμοποιήστε [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/addclone/) ή [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/addclone/) για την κλωνοποίηση διαφανειών, [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) ή [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) για την κλωνοποίηση διατάξεων και [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) για την κλωνοποίηση master. 
## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) μέθοδος


Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας στο τέλος της καθορισμένης ενότητας.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section) override
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) για κλωνοποίηση. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) για μια νέα διαφάνεια. |

### Τιμή Επιστροφής

Νέα διαφάνεια.
## Σχόλια



```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 50.0f, 300.0f, 100.0f);
presentation->get_Sections()->AddSection(u"Section 1", presentation->get_Slides()->idx_get(0));
auto section2 = presentation->get_Sections()->AppendEmptySection(u"Section 2");
presentation->get_Slides()->AddClone(presentation->get_Slides()->idx_get(0), section2);
// Τώρα η δεύτερη ενότητα περιέχει ένα αντίγραφο της πρώτης διαφάνειας.
```


## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) μέθοδος


Προσθέτει ένα αντίγραφο μιας καθορισμένης διαφάνειας στο τέλος της συλλογής.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) για κλωνοποίηση. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Διάταξη διαφάνειας για μια νέα διαφάνεια. |

### Τιμή Επιστροφής

Νέα διαφάνεια.

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) μέθοδος


Προσθέτει ένα αντίγραφο μιας καθορισμένης πηγαίας διαφάνειας στο τέλος της συλλογής. Το κατάλληλο διάταξη θα επιλεγεί αυτόματα από το καθορισμένο master (η κατάλληλη διάταξη είναι η διάταξη με τον ίδιο Τύπο ή Όνομα όπως η διάταξη της πηγαίας διαφάνειας). Εάν δεν υπάρχει κατάλληλη διάταξη, τότε η διάταξη της πηγαίας διαφάνειας θα κλωνοποιηθεί (αν το allowCloneMissingLayout είναι true) ή θα εξαχθεί PptxEditException (αν το allowCloneMissingLayout είναι false).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) για κλωνοποίηση. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Master διαφάνειας για μια νέα διαφάνεια. |
| allowCloneMissingLayout | **bool** | Εάν δεν υπάρχει κατάλληλη διάταξη στο καθορισμένο master, τότε η διάταξη της πηγαίας διαφάνειας θα κλωνοποιηθεί (αν το allowCloneMissingLayout είναι true) ή θα εξαχθεί PptxEditException (αν το allowCloneMissingLayout είναι false). |

### Τιμή Επιστροφής

Νέα διαφάνεια.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISlide](../../islide/)
* Κλάση [SlideCollection](../)
* Κλάση [ISection](../../isection/)
* Κλάση [ILayoutSlide](../../ilayoutslide/)
* Κλάση [IMasterSlide](../../imasterslide/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
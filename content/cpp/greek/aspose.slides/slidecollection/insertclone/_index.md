---
title: InsertClone()
second_title: Αναφορά API Aspose.Slides για C++
description: Εισάγει ένα αντίγραφο μιας καθορισμένης διαφάνειας στη καθορισμένη θέση της συλλογής.
type: docs
weight: 66
url: /el/aspose.slides/slidecollection/insertclone/
---
## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) μέθοδος


Εισάγει ένα αντίγραφο μιας καθορισμένης διαφάνειας στη καθορισμένη θέση της συλλογής.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide) override
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Δείκτης της νέας διαφάνειας. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) για κλωνοποίηση. |

### Τιμή Επιστροφής

Η εισαχθείσα διαφάνεια.
## Παρατηρήσεις



Κατά την κλωνοποίηση μιας διαφάνειας μεταξύ διαφορετικών παρουσιάσεων, μπορεί επίσης να κλωνοποιηθεί το master της διαφάνειας. Χρησιμοποιείται εσωτερικό μητρώο για την παρακολούθηση των αυτόματα κλωνοποιημένων master ώστε να αποτραπεί η δημιουργία πολλαπλών κλώνων του ίδιου master slide. Η χειροκίνητη κλωνοποίηση των master slide δεν θα αποτραπεί ούτε θα καταγραφεί. Εάν χρειάζεστε μεγαλύτερο έλεγχο στη διαδικασία κλωνοποίησης, χρησιμοποιήστε [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/insertclone/) ή [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/insertclone/) για κλωνοποίηση διαφανειών και [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) για κλωνοποίηση master.



Το παρακάτω παράδειγμα δείχνει πώς να κλωνοποιήσετε σε άλλη θέση μέσα στο [Presentation](../../presentation/). 
```cpp
// Δημιουργία αντικειμένου Presentation που αντιπροσωπεύει ένα αρχείο παρουσίασης
auto pres = System::MakeObject<Presentation>(u"CloneWithInSamePresentation.pptx");

// Κλωνοποίηση της επιλεγμένης διαφάνειας στο τέλος της συλλογής διαφανειών στην ίδια παρουσίαση
System::SharedPtr<ISlideCollection> slides = pres->get_Slides();
// Κλωνοποίηση της επιλεγμένης διαφάνειας στον καθορισμένο δείκτη στην ίδια παρουσίαση
slides->InsertClone(2, slides->idx_get(1));
// Αποθήκευση της τροποποιημένης παρουσίασης στο δίσκο
pres->Save(u"Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat::Pptx);
```
 Το παρακάτω παράδειγμα δείχνει πώς να κλωνοποιήσετε σε άλλη θέση μέσα στο [Presentation](../../presentation/). 
```cpp
// Δημιουργία αντικειμένου Presentation για τη φόρτωση του αρχείου πηγής παρουσίασης
auto srcPres = System::MakeObject<Presentation>(u"CloneAtEndOfAnother.pptx");

// Δημιουργία αντικειμένου Presentation για το προορισμό PPTX (όπου θα κλωνοποιηθεί η διαφάνεια)
auto destPres = System::MakeObject<Presentation>();

destPres->get_Slides()->InsertClone(2, srcPres->get_Slides()->idx_get(0));
// Αποθήκευση της προορισμού παρουσίασης στο δίσκο
destPres->Save(u"Aspose2_out.pptx", SaveFormat::Pptx);
```

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) μέθοδος


Εισάγει ένα αντίγραφο μιας καθορισμένης διαφάνειας στη καθορισμένη θέση της συλλογής.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Δείκτης της νέας διαφάνειας. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) για κλωνοποίηση. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Διαφάνεια διάταξης για μια νέα διαφάνεια. |

### Τιμή Επιστροφής

Η εισαχθείσα διαφάνεια.

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) μέθοδος


Εισάγει ένα αντίγραφο μιας καθορισμένης πηγής διαφάνειας στη καθορισμένη θέση της συλλογής. Η κατάλληλη διάταξη θα επιλεγεί αυτόματα από το καθορισμένο master (η κατάλληλη διάταξη είναι η διάταξη με τον ίδιο Type ή Name όπως η διάταξη της πηγής διαφάνειας). Εάν δεν υπάρχει κατάλληλη διάταξη, τότε η διάταξη της πηγής διαφάνειας θα κλωνοποιηθεί (αν το allowCloneMissingLayout είναι true) ή θα εξαπολυθεί PptxEditException (αν το allowCloneMissingLayout είναι false).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Δείκτης της νέας διαφάνειας. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) για κλωνοποίηση. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Master διαφάνεια για μια νέα διαφάνεια. |
| allowCloneMissingLayout | **bool** | Εάν δεν υπάρχει κατάλληλη διάταξη στον καθορισμένο master, τότε η διάταξη της πηγής διαφάνειας θα κλωνοποιηθεί (αν το allowCloneMissingLayout είναι true) ή θα εξαπολυθεί PptxEditException (αν το allowCloneMissingLayout είναι false). |

### Τιμή Επιστροφής

Η εισαχθείσα διαφάνεια.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [SlideCollection](../)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
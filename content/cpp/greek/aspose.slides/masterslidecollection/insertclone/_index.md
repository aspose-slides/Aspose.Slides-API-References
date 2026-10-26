---
title: InsertClone()
second_title: Aspose.Slides για C++ API Αναφορά
description: Εισάγει ένα αντίγραφο μιας καθορισμένης κύριας διαφάνειας στη συγκεκριμένη θέση της συλλογής. Οι συνδεδεμένες διαφάνειες διάταξης θα αντιγραφούν επίσης.
type: docs
weight: 105
url: /el/aspose.slides/masterslidecollection/insertclone/
---
## MasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) μέθοδος

Εισάγει ένα αντίγραφο μιας καθορισμένης κύριας διαφάνειας στη συγκεκριμένη θέση της συλλογής. Τα συνδεδεμένα διαφάνειες διάταξης θα αντιγραφούν επίσης.

```cpp
System::SharedPtr<IMasterSlide> Aspose::Slides::MasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Δείκτης της νέας διαφάνειας. |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) για κλωνοποίηση. |

### Τιμή Επιστροφής

Η εισαχθείσα κύρια διαφάνεια.

## Σχόλια

Το παρακάτω παράδειγμα δείχνει πώς να κλωνοποιήσετε την κύρια διαφάνεια σε ένα άλλο PowerPoint [Presentation](../../presentation/).
```cpp
// Δημιουργία αντικειμένου Presentation για φόρτωση του πηγαίου αρχείου παρουσίασης
auto srcPres = System::MakeObject<Presentation>(u"CloneToAnotherPresentationWithMaster.pptx");

// Δημιουργία αντικειμένου Presentation για την προορισμένη παρουσίαση (όπου θα κλωνοποιηθεί η διαφάνεια)
auto destPres = System::MakeObject<Presentation>();

// Δημιουργία αντικειμένου ISlide από τη συλλογή διαφανειών στην πηγαία παρουσίαση μαζί με
// Κύρια διαφάνεια
auto sourceSlide = srcPres->get_Slides()->idx_get(0);
auto sourceMaster = sourceSlide->get_LayoutSlide()->get_MasterSlide();
// Λήψη κύριων διαφανειών της προορισμένης παρουσίασης
auto masters = destPres->get_Masters();
// Κλωνοποίηση της επιθυμητής κύριας διαφάνειας από την πηγαία παρουσίαση στη συλλογή κυρίων διαφανειών της
// Προορισμένη παρουσίαση
System::SharedPtr<IMasterSlide> iSlide = masters->AddClone(sourceMaster);
// Συλλογή διαφανειών στην προορισμένη παρουσίαση
auto slides = destPres->get_Slides();
// Κλωνοποίηση της πηγαίας διαφάνειας στη συλλογή διαφανειών του προορισμού.
slides->AddClone(sourceSlide, iSlide, true);
// Αποθήκευση της προορισμένης παρουσίασης στο δίσκο
destPres->Save(u"CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMasterSlide](../../imasterslide/)
* Κλάση [MasterSlideCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
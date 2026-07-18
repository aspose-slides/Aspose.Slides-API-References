---
title: set_PresentationLockingBehavior()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Αυτή η ιδιότητα καθορίζει εάν ένα αντικείμενο της κλάσης Presentation μπορεί να είναι ιδιοκτήτης της πηγής - αρχείου ή ροής κατά τη διάρκεια της ζωής του αντικειμένου. Εάν το αντικείμενο είναι ιδιοκτήτης, κλειδώνει την πηγή. Αυτό βοηθά στη βελτίωση της κατανάλωσης μνήμης και της απόδοσης κατά την εργασία με BLOBs, αλλά η πηγή (ροή ή αρχείο) δεν μπορεί να αλλάξει κατά τη διάρκεια της ζωής του αντικειμένου Presentation. Αυτό είναι ένα παράδειγμα:"
type: docs
weight: 14
url: /el/aspose.slides/iblobmanagementoptions/set_presentationlockingbehavior/
---
## IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior) μέθοδος

Αυτή η ιδιότητα καθορίζει εάν ένα αντικείμενο της κλάσης [Presentation](../../presentation/) μπορεί να είναι ιδιοκτήτης της πηγής - αρχείου ή ροής κατά τη διάρκεια της ζωής του αντικειμένου. Εάν το αντικείμενο είναι ιδιοκτήτης, κλειδώνει την πηγή. Αυτό βοηθά στη βελτίωση της κατανάλωσης μνήμης και της απόδοσης κατά την εργασία με BLOBs, αλλά η πηγή (ροή ή αρχείο) δεν μπορεί να τροποποιηθεί κατά τη διάρκεια της ζωής του αντικειμένου [Presentation](../../presentation/). Αυτό είναι ένα παράδειγμα:

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior value)=0
```

## Σχόλια

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // Θα προκληθεί IOException επειδή το pres.pptx είναι κλειδωμένο για τη διάρκεια ζωής ενός Presentation
    // File::Delete(u"pres.pptx");
}
// μετά την καταστροφή του αντικειμένου Presentation, το αρχείο ξεκλειδώνεται και μπορεί να διαγραφεί
IO::File::Delete(u"pres.pptx");
```

## Δείτε επίσης

* Απαρίθμηση [PresentationLockingBehavior](../../presentationlockingbehavior/)
* Κλάση [IBlobManagementOptions](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
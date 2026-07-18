---
title: get_PresentationLockingBehavior()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Αυτή η ιδιότητα ορίζει αν ένα στιγμιότυπο της κλάσης Presentation μπορεί να είναι ιδιοκτήτης της πηγής - αρχείου ή ροής κατά τη διάρκεια της ζωής του στιγμιότυπου. Αν το στιγμιότυπο είναι ιδιοκτήτης, κλειδώνει την πηγή. Αυτό βοηθά στη βελτίωση της κατανάλωσης μνήμης και της απόδοσης ενώ εργάζεστε με BLOBs, αλλά η πηγή (ροή ή αρχείο) δεν μπορεί να αλλάξει κατά τη διάρκεια της ζωής του στιγμιότυπου του Presentation. Αυτό είναι ένα παράδειγμα:"
type: docs
weight: 1
url: /el/aspose.slides/iblobmanagementoptions/get_presentationlockingbehavior/
---
## IBlobManagementOptions::get_PresentationLockingBehavior() μέθοδος


Αυτή η ιδιότητα ορίζει αν ένα στιγμιότυπο της [Presentation](../../presentation/) κλάσης μπορεί να είναι ιδιοκτήτης της πηγής - αρχείου ή ροής κατά τη διάρκεια της ζωής του στιγμιότυπου. Αν το στιγμιότυπο είναι ιδιοκτήτης, κλειδώνει την πηγή. Αυτό βοηθά στη βελτίωση της κατανάλωσης μνήμης και της απόδοσης ενώ εργάζεστε με BLOBs, αλλά η πηγή (ροή ή αρχείο) δεν μπορεί να αλλάξει κατά τη διάρκεια της ζωής του στιγμιότυπου του [Presentation](../../presentation/). Αυτό είναι ένα παράδειγμα:

```cpp
virtual Aspose::Slides::PresentationLockingBehavior Aspose::Slides::IBlobManagementOptions::get_PresentationLockingBehavior()=0
```

## Σχόλια



```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // Θα εξαπολυθεί IOException επειδή το pres.pptx είναι κλειδωμένο για όλη τη διάρκεια ζωής του Presentation
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
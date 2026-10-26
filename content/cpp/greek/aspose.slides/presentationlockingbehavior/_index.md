---
title: PresentationLockingBehavior
second_title: Aspose.Slides για C++ Αναφορά API
description: "Αντιπροσωπεύει τη συμπεριφορά σχετικά με τη διαχείριση της πηγής IPresentation (αρχείο ή System::IO::Stream) κατά τη φόρτωση και εργασία με ένα στιγμιότυπο του IPresentation."
type: docs
weight: 6748
url: /el/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior enum

Αντιπροσωπεύει τη συμπεριφορά σχετικά με τη διαχείριση της πηγής [IPresentation](../ipresentation/) (αρχείο ή [System::IO::Stream](../../system.io/stream/)) κατά τη φόρτωση και εργασία με ένα στιγμιότυπο του [IPresentation](../ipresentation/).

```cpp
enum class PresentationLockingBehavior
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| LoadAndRelease | 0 | Η πηγή θα κλειδωθεί μόνο για τη διάρκεια της εκτέλεσης του κατασκευαστή [IPresentation](../ipresentation/). |
| KeepLocked | 1 | Η πηγή θα κλειδωθεί για ολόκληρη τη διάρκεια του στιγμιότυπου [IPresentation](../ipresentation/), μέχρι να διαγραφεί. |

## Παρατηρήσεις

Η πηγή είναι η παράμετρος που περνάται στον κατασκευαστή [IPresentation](../ipresentation/). Στο παρακάτω παράδειγμα, η πηγή είναι το αρχείο "pres.pptx":

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
}
```

Για αυτό το παράδειγμα, η πηγή (αρχείο "pres.pptx") θα κλειδωθεί για τη διάρκεια του στιγμιότυπου [IPresentation](../ipresentation/), δηλαδή δεν μπορεί να αλλάξει ή να διαγραφεί από άλλη διαδικασία.

## Δείτε επίσης

* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)
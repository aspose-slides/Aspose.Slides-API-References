---
title: SetLicense()
second_title: Aspose.Slides για C++ API Reference
description: Δίνει άδεια στο στοιχείο.
type: docs
weight: 1
url: /el/aspose.slides/ilicense/setlicense/
---
## ILicense::SetLicense(System::String) μέθοδος

Δίνει άδεια στο στοιχείο.

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::String licenseName)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | Μπορεί να είναι πλήρες ή σύντομο όνομα αρχείου ή όνομα ενσωματωμένου πόρου. Χρησιμοποιήστε μια κενή συμβολοσειρά για να μεταβείτε στη λειτουργία αξιολόγησης. |

## Παρατηρήσεις

Προσπαθεί να βρει την άδεια στις ακόλουθες θέσεις:

1. Συγκεκριμένη διαδρομή.
2. Ο φάκελος της συναρμολόγησης του στοιχείου.
3. Ο φάκελος της συναρμολόγησης κλήσης του πελάτη.
4. Ο φάκελος της κύριας συναρμολόγησης.
5. Ένας ενσωματωμένος πόρος στη συναρμολόγηση κλήσης του πελάτη.

**Σημείωση:** Στο .NET Compact Framework, προσπαθεί να βρει την άδεια μόνο σε αυτές τις τοποθεσίες:

1. Συγκεκριμένη διαδρομή.
2. Ένας ενσωματωμένος πόρος στη συναρμολόγηση κλήσης του πελάτη.

Σε αυτό το παράδειγμα, θα γίνει προσπάθεια να βρεθεί ένα αρχείο άδειας με το όνομα MyLicense.lic στον φάκελο που περιέχει το στοιχείο, στον φάκελο που περιέχει τη συναρμολόγηση κλήσης, στον φάκελο της κύριας συναρμολόγησης και, τέλος, στους ενσωματωμένους πόρους της συναρμολόγησης κλήσης. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## ILicense::SetLicense(System::SharedPtr\<System::IO::Stream\>) μέθοδος

Δίνει άδεια στο στοιχείο.

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::SharedPtr<System::IO::Stream> stream)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Μια ροή που περιέχει την άδεια. |

## Παρατηρήσεις

Χρησιμοποιήστε αυτή τη μέθοδο για να φορτώσετε μια άδεια από μια ροή.

```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [ILicense](../)
* Κλάση [Stream](../../../system.io/stream/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
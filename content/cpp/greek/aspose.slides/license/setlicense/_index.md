---
title: SetLicense()
second_title: Aspose.Slides για C++ API Αναφορά
description: Χορηγεί την άδεια στο στοιχείο.
type: docs
weight: 14
url: /el/aspose.slides/license/setlicense/
---
## License::SetLicense(System::String) μέθοδος


Χορηγεί την άδεια στο στοιχείο.

```cpp
void Aspose::Slides::License::SetLicense(System::String licenseName) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | Μπορεί να είναι πλήρες ή σύντομο όνομα αρχείου ή όνομα ενσωματωμένου πόρου. Χρησιμοποιήστε κενή συμβολοσειρά για να μεταβείτε σε λειτουργία αξιολόγησης. |
## Παρατηρήσεις



Προσπαθεί να βρει την άδεια στις ακόλουθες θέσεις:

1. Συγκεκριμένη διαδρομή.

2. Ο φάκελος της συναρμολόγησης του στοιχείου.

3. Ο φάκελος της κλήσης συναρμολόγησης του πελάτη.

4. Ο φάκελος της κύριας συναρμολόγησης.

5. Ένας ενσωματωμένος πόρος στη συναρμολόγηση κλήσης του πελάτη.

**Σημείωση:** Στο .NET Compact Framework, προσπαθεί να βρει την άδεια μόνο σε αυτές τις θέσεις:

1. Συγκεκριμένη διαδρομή.

2. Ένας ενσωματωμένος πόρος στη συναρμολόγηση κλήσης του πελάτη.

Σε αυτό το παράδειγμα, θα γίνει προσπάθεια να βρεθεί ένα αρχείο άδειας με όνομα MyLicense.lic στον φάκελο που περιέχει το στοιχείο, στον φάκελο που περιέχει τη συναρμολόγηση κλήσης, στον φάκελο της κύριας συναρμολόγησης και στη συνέχεια στους ενσωματωμένους πόρους της συναρμολόγησης κλήσης. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) μέθοδος


Χορηγεί την άδεια στο στοιχείο.

```cpp
void Aspose::Slides::License::SetLicense(System::SharedPtr<System::IO::Stream> stream) override
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

* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [License](../)
* Κλάση [Stream](../../../system.io/stream/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
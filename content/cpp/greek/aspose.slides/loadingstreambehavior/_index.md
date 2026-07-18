---
title: LoadingStreamBehavior
second_title: Aspose.Slides για C++ Αναφορά API
description: "Το System::IO::Stream που περνιέται σε μια μέθοδο θεωρείται ως Binary Large Object (BLOB) (δείτε την περιγραφή του IBlobManagementOptions). Οι τιμές αυτής της απαρίθμησης καθορίζουν πώς πρέπει να αντιμετωπιστεί το System::IO::Stream όταν περνιέται στη μέθοδο. Ανάλογα με τις απαιτήσεις, μπορούν να ληφθούν διαφορετικές αποφάσεις για την παροχή της πιο αποδοτικής συμπεριφοράς."
type: docs
weight: 6735
url: /el/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior enum

Το [System::IO::Stream](../../system.io/stream/) που περνιέται σε μια μέθοδο θεωρείται ως Binary Large Object (BLOB) (δείτε την περιγραφή του [IBlobManagementOptions](../iblobmanagementoptions/)). Οι τιμές αυτής της απαρίθμησης καθορίζουν πώς πρέπει να αντιμετωπιστεί το [System::IO::Stream](../../system.io/stream/) όταν περνιέται στη μέθοδο. Ανάλογα με τις απαιτήσεις, μπορούν να ληφθούν διαφορετικές αποφάσεις για την παροχή της πιο αποδοτικής συμπεριφοράς.

```cpp
enum class LoadingStreamBehavior
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| ReadStreamAndRelease | 0 | Η ροή θα διαβαστεί μέχρι το τέλος και έπειτα θα απελευθερωθεί - δηλαδή θα εξασφαλιστεί ότι αυτή η ροή δεν θα χρησιμοποιηθεί από το αντικείμενο [IPresentation](../ipresentation/) στο μέλλον. Μπορεί να κλείσει από τον κώδικα του πελάτη ή να χρησιμοποιηθεί με οποιονδήποτε άλλο τρόπο. |
| KeepLocked | 1 | Η ροή θα κλειδωθεί μέσα στο αντικείμενο [IPresentation](../ipresentation/), δηλαδή η ιδιοκτησία της ροής θα μεταβιβαστεί. Το αντικείμενο [IPresentation](../ipresentation/) θα είναι υπεύθυνο για τη σωστή απελευθέρωση της ροής όταν αυτό το αντικείμενο απελευθερωθεί. Αυτή η συμπεριφορά είναι εξαιρετικά χρήσιμη όταν πρέπει να σειριοποιήσετε ένα μεγάλο αρχείο BLOB (όπως ένα μεγάλο βίντεο ή ήχο - δείτε την περιγραφή του [IBlobManagementOptions](../iblobmanagementoptions/)) και θέλετε να αποτρέψετε τη φόρτωση αυτού του αρχείου στη μνήμη ή άλλα προβλήματα απόδοσης. Μπορείτε απλώς να ανοίξετε το [System::IO::FileStream](../../system.io/filestream/) για αυτό το αρχείο και να το περάσετε σε μια μέθοδο, επιλέγοντας το [LoadingStreamBehavior::KeepLocked](./) LoadingStreamBehavior. |

## Δείτε επίσης

* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)
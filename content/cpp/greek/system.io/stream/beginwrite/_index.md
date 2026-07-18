---
title: BeginWrite()
second_title: Αναφορά API Aspose.Slides για C++
description: Ξεκινά μια ασύγχρονη λειτουργία εγγραφής.
type: docs
weight: 170
url: /el/system.io/stream/beginwrite/
---
## Stream::BeginWrite(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) μέθοδος

Ξεκινά μια ασύγχρονη λειτουργία εγγραφής.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ένα buffer που περιέχει τα δεδομένα που θα γραφτούν |
| offset | int | Μια μετατόπιση με βάση το 0 στο **buffer** που υποδεικνύει τη θέση από την οποία αρχίζουν τα δεδομένα προς εγγραφή |
| count | int | Ο αριθμός των byte που θα γραφτούν |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | Μία callback που θα κληθεί όταν ολοκληρωθεί η λειτουργία |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Δεδομένα που παρέχονται από το χρήστη και χρησιμοποιούνται για τη μοναδική ταυτοποίηση κάθε ασύγχρονης λειτουργίας εγγραφής |

### Τιμή επιστροφής

Ένα αντικείμενο [IAsyncResult](../../../system/iasyncresult/) που αντιπροσωπεύει την εκκινημένη ασύγχρονη λειτουργία εγγραφής

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Κλάση [IAsyncResult](../../../system/iasyncresult/)
* Κλάση [Object](../../../system/object/)
* Κλάση [Stream](../)
* Χώρος ονομάτων [System::IO](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
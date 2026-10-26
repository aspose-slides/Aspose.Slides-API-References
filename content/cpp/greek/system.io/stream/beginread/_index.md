---
title: BeginRead()
second_title: Aspose.Slides για C++ Αναφορά API
description: Εκκινεί μια ασύγχρονη λειτουργία ανάγνωσης.
type: docs
weight: 157
url: /el/system.io/stream/beginread/
---
## Stream::BeginRead(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) μέθοδος

Εκκινεί μια ασύγχρονη λειτουργία ανάγνωσης.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginRead(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```

### Παραμέτρους

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ένα buffer για ανάγνωση |
| offset | int | Ένα offset με βάση το 0 στο **buffer** που υποδεικνύει τη θέση από την οποία ξεκινά η εγγραφή των δεδομένων που διαβάζονται |
| count | int | Ο αριθμός των bytes για ανάγνωση |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | Μία callback που θα κληθεί όταν ολοκληρωθεί η λειτουργία |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Δεδομένα που παρέχονται από το χρήστη, χρησιμοποιούνται για την μοναδική ταυτοποίηση κάθε ασύγχρονης λειτουργίας ανάγνωσης |

### Return Value

Ένα αντικείμενο [IAsyncResult](../../../system/iasyncresult/) που αντιπροσωπεύει την εκκινημένη ασύγχρονη λειτουργία ανάγνωσης

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Κλάση [IAsyncResult](../../../system/iasyncresult/)
* Κλάση [Object](../../../system/object/)
* Κλάση [Stream](../)
* Χώρος ονομάτων [System::IO](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
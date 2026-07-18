---
title: BeginWrite()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ξεκινά μια ασύγχρονη λειτουργία εγγραφής.
type: docs
weight: 274
url: /el/system.net.sockets/networkstream/beginwrite/
---
## NetworkStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) μέθοδος


Ξεκινά μια ασύγχρονη λειτουργία εγγραφής.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ένα buffer που περιέχει δεδομένα προς εγγραφή. |
| offset | **int32_t** | Η μετατόπιση σε bytes στον καθορισμένο πίνακα. |
| size | **int32_t** | Ο αριθμός των bytes που θα εγγραφούν. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Μια callback που καλείται όταν ολοκληρωθεί η λειτουργία. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Δεδομένα που παρέχονται από τον χρήστη και χρησιμοποιούνται για μοναδική αναγνώριση κάθε ασύγχρονης λειτουργίας εγγραφής. |

### Τιμή Επιστροφής

Ένα αντικείμενο [IAsyncResult](../../../system/iasyncresult/) που αντιπροσωπεύει την ξεκίνητη ασύγχρονη λειτουργία εγγραφής.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Κλάση [IAsyncResult](../../../system/iasyncresult/)
* Κλάση [Object](../../../system/object/)
* Κλάση [NetworkStream](../)
* Χώρος ονομάτων [System::Net::Sockets](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
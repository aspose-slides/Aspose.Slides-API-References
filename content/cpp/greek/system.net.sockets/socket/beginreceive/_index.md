---
title: BeginReceive()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ξεκινά μια ασύγχρονη λειτουργία εγγραφής.
type: docs
weight: 521
url: /el/system.net.sockets/socket/beginreceive/
---
## Socket::BeginReceive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) μέθοδος

Ξεκινά μια ασύγχρονη λειτουργία εγγραφής.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginReceive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ένας buffer όπου θα εκχωρηθούν τα ληφθέντα δεδομένα. |
| offset | **int32_t** | Η μετατόπιση σε bytes στον καθορισμένο πίνακα. |
| size | **int32_t** | Ο αριθμός των bytes στον καθορισμένο πίνακα ξεκινώντας από την παράμετρο 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά λήψης. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Μια callback που θα κληθεί όταν ολοκληρωθεί η λειτουργία. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Δεδομένα που παρέχονται από τον χρήστη και χρησιμοποιούνται για την μοναδική ταυτοποίηση κάθε ασύγχρονης λειτουργίας λήψης. |

### Τιμή Επιστροφής

Ένα αντικείμενο [IAsyncResult](../../../system/iasyncresult/) που αντιπροσωπεύει τη ξεκίνητη ασύγχρονη λειτουργία λήψης.

## Δείτε επίσης

* Απαρίθμηση [SocketFlags](../../socketflags/)
* ΟρισμόςΤύπου [SharedPtr](../../../system/sharedptr/)
* ΟρισμόςΤύπου [ArrayPtr](../../../system/arrayptr/)
* ΟρισμόςΤύπου [AsyncCallback](../../../system/asynccallback/)
* Κλάση [IAsyncResult](../../../system/iasyncresult/)
* Κλάση [Object](../../../system/object/)
* Κλάση [Socket](../)
* Χώρος ονομάτων [System::Net::Sockets](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
---
title: BeginWrite()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ξεκινά μια ασύγχρονη λειτουργία εγγραφής.
type: docs
weight: 443
url: /el/system.net.security/sslstream/beginwrite/
---
## SslStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) μέθοδος

Ξεκινά μια ασύγχρονη λειτουργία εγγραφής.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ο πίνακας byte όπου θα γραφτούν τα δεδομένα. |
| offset | **int32_t** | Η μετατόπιση σε bytes στον καθορισμένο πίνακα. |
| count | **int32_t** | Ο αριθμός των bytes που θα γραφτούν. |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | Μια κλήση επιστροφής (callback) που θα κληθεί όταν η λειτουργία ολοκληρωθεί. |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Δεδομένα που παρέχονται από το χρήστη και χρησιμοποιούνται για την μοναδική ταυτοποίηση κάθε ασύγχρονης λειτουργίας εγγραφής. |

### Τιμή Επιστροφής

Ένα αντικείμενο [IAsyncResult](../../../system/iasyncresult/) που αντιπροσωπεύει την έναρξη της ασύγχρονης λειτουργίας εγγραφής.

## Δείτε επίσης

* Τύπος [SharedPtr](../../../system/sharedptr/)
* Τύπος [ArrayPtr](../../../system/arrayptr/)
* Τύπος [AsyncCallback](../../../system/asynccallback/)
* Κλάση [IAsyncResult](../../../system/iasyncresult/)
* Κλάση [Object](../../../system/object/)
* Κλάση [SslStream](../)
* Χώρος ονομάτων [System::Net::Security](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
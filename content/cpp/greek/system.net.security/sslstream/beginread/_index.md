---
title: BeginRead()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Ξεκινά μια ασύγχρονη λειτουργία ανάγνωσης.
type: docs
weight: 417
url: /el/system.net.security/sslstream/beginread/
---
## SslStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) μέθοδος

Ξεκινά μια ασύγχρονη λειτουργία ανάγνωσης.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ο πίνακας byte από τον οποίο διαβάζονται τα δεδομένα. |
| offset | **int32_t** | Η μετατόπιση σε bytes στον καθορισμένο πίνακα. |
| count | **int32_t** | Ο αριθμός των bytes προς ανάγνωση. |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | Μια κλήση επιστροφής που θα κληθεί όταν ολοκληρωθεί η λειτουργία. |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Δεδομένα που παρέχονται από τον χρήστη και χρησιμοποιούνται για τη μοναδική αναγνώριση κάθε ασύγχρονης λειτουργίας ανάγνωσης. |

### Τιμή Επιστροφής

Ένα αντικείμενο [IAsyncResult](../../../system/iasyncresult/) που αντιπροσωπεύει την εκκίνηση της ασύγχρονης λειτουργίας ανάγνωσης.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Κλάση [IAsyncResult](../../../system/iasyncresult/)
* Κλάση [Object](../../../system/object/)
* Κλάση [SslStream](../)
* Χώρος ονομάτων [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)
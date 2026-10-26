---
title: BeginGetResponse()
second_title: Αναφορά API του Aspose.Slides για C++
description: Προκαλεί μια ασύγχρονη αίτηση για τον πόρο.
type: docs
weight: 170
url: /el/system.net/filewebrequest/begingetresponse/
---
## FileWebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) μέθοδος

Προκαλεί μια ασύγχρονη αίτηση για τον πόρο.

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Μια κλήση επιστροφής που θα κληθεί όταν ολοκληρωθεί η λειτουργία. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Δεδομένα που παρέχονται από τον χρήστη και χρησιμοποιούνται για μοναδική αναγνώριση κάθε ασύγχρονης λειτουργίας. |

### Τιμή Επιστροφής

Ένα αντικείμενο [IAsyncResult](../../../system/iasyncresult/) που αντιπροσωπεύει τη διεργασία ασύγχρονης αίτησης που ξεκίνησε.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Κλάση [IAsyncResult](../../../system/iasyncresult/)
* Κλάση [Object](../../../system/object/)
* Κλάση [FileWebRequest](../)
* Ονοματοχώρος [System::Net](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
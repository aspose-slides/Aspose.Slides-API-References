---
title: BeginGetResponse()
second_title: Αναφορά API Aspose.Slides για C++
description: Ξεκινά ένα ασύγχρονο αίτημα για τον πόρο.
type: docs
weight: 274
url: /el/system.net/webrequest/begingetresponse/
---
## WebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) μέθοδος


Ξεκινά ένα ασύγχρονο αίτημα για τον πόρο.

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Μία συνάρτηση επανάκλησης που θα κληθεί όταν ολοκληρωθεί η λειτουργία. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Δεδομένα που παρέχονται από τον χρήστη και χρησιμοποιούνται για τη μοναδική ταυτοποίηση κάθε ασύγχρονης λειτουργίας. |

### Τιμή επιστροφής

Ένα αντικείμενο [IAsyncResult](../../../system/iasyncresult/) που αντιπροσωπεύει τη ξεκινημένη ασύγχρονη λειτουργία.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Κλάση [IAsyncResult](../../../system/iasyncresult/)
* Κλάση [Object](../../../system/object/)
* Κλάση [WebRequest](../)
* Ονομαχώρος [System::Net](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
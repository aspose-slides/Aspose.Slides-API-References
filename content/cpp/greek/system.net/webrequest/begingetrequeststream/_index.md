---
title: BeginGetRequestStream()
second_title: Αναφορά API Aspose.Slides για C++
description: Εκκινεί μια ασύγχρονη λειτουργία για λήψη ρεύματος για εγγραφή δεδομένων στον πόρο.
type: docs
weight: 300
url: /el/system.net/webrequest/begingetrequeststream/
---
## WebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) μέθοδος

Εκκινεί μια ασύγχρονη λειτουργία για την λήψη ρεύματος για εγγραφή δεδομένων στον πόρο.

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state)=0
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Μια κλήση επιστροφής που θα κληθεί όταν η λειτουργία ολοκληρωθεί. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Δεδομένα που παρέχονται από το χρήστη και χρησιμοποιούνται για την μοναδική ταυτοποίηση κάθε ασύγχρονης λειτουργίας. |

### Τιμή επιστροφής

Ένα αντικείμενο [IAsyncResult](../../../system/iasyncresult/) που αντιπροσωπεύει την έναρξη της ασύγχρονης λειτουργίας.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)
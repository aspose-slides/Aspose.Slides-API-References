---
title: BeginGetRequestStream()
second_title: Aspose.Slides για C++ API αναφορά
description: Εκκινεί μια ασύγχρονη λειτουργία για τη λήψη ροής για την εγγραφή δεδομένων στον πόρο.
type: docs
weight: 144
url: /el/system.net/filewebrequest/begingetrequeststream/
---
## FileWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) μέθοδος

Εκκινεί μια ασύγχρονη λειτουργία για την απόκτηση ροής εγγραφής δεδομένων στον πόρο.

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Μια συνάρτηση επανάκλησης που καλείται όταν ολοκληρωθεί η λειτουργία. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Δεδομένα που παρέχονται από τον χρήστη και χρησιμοποιούνται για τη μοναδική αναγνώριση κάθε ασύγχρονης λειτουργίας. |

### Τιμή Επιστροφής

Ένα αντικείμενο [IAsyncResult](../../../system/iasyncresult/) που αντιπροσωπεύει την έναρξη της ασύγχρονης λειτουργίας.

## Δείτε επίσης

* typedef [SharedPtr](../../../system/sharedptr/)
* typedef [AsyncCallback](../../../system/asynccallback/)
* κλάση [IAsyncResult](../../../system/iasyncresult/)
* κλάση [Object](../../../system/object/)
* κλάση [FileWebRequest](../)
* χώρο ονομάτων [System::Net](../../)
* βιβλιοθήκη [Aspose.Slides](../../../)
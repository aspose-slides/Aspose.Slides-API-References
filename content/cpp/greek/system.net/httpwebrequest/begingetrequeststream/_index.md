---
title: BeginGetRequestStream()
second_title: Αναφορά API Aspose.Slides για C++
description: Αρχίζει μια ασύγχρονη λειτουργία για λήψη ροής ώστε να γραφτούν δεδομένα στον πόρο.
type: docs
weight: 469
url: /el/system.net/httpwebrequest/begingetrequeststream/
---
## HttpWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) μέθοδος

Αρχίζει μια ασύγχρονη λειτουργία για λήψη ροής ώστε να γραφτούν δεδομένα στον πόρο.

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Μια callback που θα κληθεί όταν ολοκληρωθεί η λειτουργία. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Δεδομένα που παρέχονται από τον χρήστη και χρησιμοποιούνται για τη μοναδική ταυτοποίηση κάθε ασύγχρονης λειτουργίας. |

### Τιμή Επιστροφής

Ένα αντικείμενο [IAsyncResult](../../../system/iasyncresult/) που αντιπροσωπεύει την έναρξη της ασύγχρονης λειτουργίας.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Κλάση [IAsyncResult](../../../system/iasyncresult/)
* Κλάση [Object](../../../system/object/)
* Κλάση [HttpWebRequest](../)
* Χώρος ονομάτων [System::Net](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
---
title: EndGetRequestStream()
second_title: Aspose.Slides για C++ API Αναφορά
description: Περιμένει μέχρι η καθορισμένη ασύγχρονη λειτουργία λήψης ρεύματος να ολοκληρωθεί.
type: docs
weight: 482
url: /el/system.net/httpwebrequest/endgetrequeststream/
---
## HttpWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) μέθοδος

Waits until the specified asynchronous operation to get a stream completes.

```cpp
System::SharedPtr<IO::Stream> System::Net::HttpWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Ένα αντικείμενο [IAsyncResult](../../../system/iasyncresult/) που αντιπροσωπεύει μια ασύγχρονη λειτουργία για λήψη ρεύματος. |

## Τιμή Επιστροφής

Το ρεύμα για εγγραφή δεδομένων στον πόρο.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Stream](../../../system.io/stream/)
* Κλάση [IAsyncResult](../../../system/iasyncresult/)
* Κλάση [HttpWebRequest](../)
* Χώρος ονομάτων [System::Net](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
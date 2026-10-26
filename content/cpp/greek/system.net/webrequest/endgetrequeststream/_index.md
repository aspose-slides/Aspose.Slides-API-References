---
title: EndGetRequestStream()
second_title: Aspose.Slides για C++ Αναφορά API
description: Περιμένει μέχρι να ολοκληρωθεί η καθορισμένη ασύγχρονη λειτουργία λήψης ροής.
type: docs
weight: 313
url: /el/system.net/webrequest/endgetrequeststream/
---
## WebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) μέθοδος

Περιμένει μέχρι να ολοκληρωθεί η καθορισμένη ασύγχρονη λειτουργία λήψης ροής.

```cpp
virtual System::SharedPtr<IO::Stream> System::Net::WebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Ένα [IAsyncResult](../../../system/iasyncresult/) αντικείμενο που αντιπροσωπεύει μια ασύγχρονη λειτουργία λήψης ροής. |

### Τιμή Επιστροφής

Η ροή για την εγγραφή δεδομένων στον πόρο.

## Δείτε Επίσης

* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [Stream](../../../system.io/stream/)
* Κλάση [IAsyncResult](../../../system/iasyncresult/)
* Κλάση [WebRequest](../)
* Χώρος ονομάτων [System::Net](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
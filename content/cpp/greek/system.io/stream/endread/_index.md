---
title: EndRead()
second_title: Aspose.Slides για C++ API Αναφορά
description: Περιμένει μέχρι να ολοκληρωθεί η καθορισμένη ασύγχρονη λειτουργία ανάγνωσης.
type: docs
weight: 183
url: /el/system.io/stream/endread/
---
## Stream::EndRead(System::SharedPtr\<System::IAsyncResult\>) μέθοδος

Περιμένει μέχρι να ολοκληρωθεί η καθορισμένη ασύγχρονη λειτουργία ανάγνωσης.

```cpp
virtual int System::IO::Stream::EndRead(System::SharedPtr<System::IAsyncResult> asyncResult)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[System::IAsyncResult](../../../system/iasyncresult/)\> | An [IAsyncResult](../../../system/iasyncresult/) object that represents an asynchronous read operation |

### Τιμή Επιστροφής

Ο αριθμός των byte που διαβάστηκαν κατά τη διάρκεια της λειτουργίας ανάγνωσης που αντιπροσωπεύεται από **asyncResult**

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IAsyncResult](../../../system/iasyncresult/)
* Κλάση [Stream](../)
* Χώρος ονομάτων [System::IO](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
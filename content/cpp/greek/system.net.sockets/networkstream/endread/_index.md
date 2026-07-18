---
title: EndRead()
second_title: Aspose.Slides για την Αναφορά API C++
description: Περιμένει μέχρι να ολοκληρωθεί η καθορισμένη ασύγχρονη λειτουργία ανάγνωσης.
type: docs
weight: 261
url: /el/system.net.sockets/networkstream/endread/
---
## NetworkStream::EndRead(System::SharedPtr\<IAsyncResult\>) μέθοδος

Περιμένει μέχρι να ολοκληρωθεί η καθορισμένη ασύγχρονη λειτουργία ανάγνωσης.

```cpp
int32_t System::Net::Sockets::NetworkStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Ένα [IAsyncResult](../../../system/iasyncresult/) αντικείμενο που αντιπροσωπεύει μια ασύγχρονη λειτουργία ανάγνωσης |

### Τιμή Επιστροφής

Ο αριθμός των byte που διαβαστήκαν κατά τη λειτουργία ανάγνωσης που αναπαρίσταται από **asyncResult**

## Δείτε επίσης

* Τυπική Δήλωση [SharedPtr](../../../system/sharedptr/)
* Κλάση [IAsyncResult](../../../system/iasyncresult/)
* Κλάση [NetworkStream](../)
* Χώρος ονομάτων [System::Net::Sockets](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
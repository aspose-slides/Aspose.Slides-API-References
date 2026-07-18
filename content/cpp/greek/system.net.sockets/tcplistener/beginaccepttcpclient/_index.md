---
title: BeginAcceptTcpClient()
second_title: Aspose.Slides για το API αναφορά C++
description: Ξεκινά μια ασύγχρονη λειτουργία αποδοχής.
type: docs
weight: 170
url: /el/system.net.sockets/tcplistener/beginaccepttcpclient/
---
## TcpListener::BeginAcceptTcpClient(AsyncCallback, System::SharedPtr\<Object\>) μέθοδος

Ξεκινά μια ασύγχρονη λειτουργία αποδοχής.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptTcpClient(AsyncCallback callback, System::SharedPtr<Object> state)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Μία συνάρτηση ανάκλησης που θα κληθεί όταν ολοκληρωθεί η λειτουργία. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Δεδομένα που παρέχονται από τον χρήστη και χρησιμοποιούνται για τη μοναδική ταυτοποίηση κάθε ασύγχρονης λειτουργίας σύνδεσης. |

### Τιμή Επιστροφής

Ένα αντικείμενο [IAsyncResult](../../../system/iasyncresult/) που αντιπροσωπεύει την αρχικοποιημένη ασύγχρονη λειτουργία αποδοχής.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Κλάση [IAsyncResult](../../../system/iasyncresult/)
* Κλάση [Object](../../../system/object/)
* Κλάση [TcpListener](../)
* Χώρος ονομάτων [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
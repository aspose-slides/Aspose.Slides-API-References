---
title: EndSend()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Περιμένει μέχρι να ολοκληρωθεί η καθορισμένη ασύγχρονη λειτουργία αποστολής.
type: docs
weight: 508
url: /el/system.net.sockets/socket/endsend/
---
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>) μέθοδος

Περιμένει μέχρι να ολοκληρωθεί η καθορισμένη ασύγχρονη λειτουργία αποστολής.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Ένα αντικείμενο [IAsyncResult](../../../system/iasyncresult/) που αντιπροσωπεύει μια ασύγχρονη λειτουργία αποστολής. |

### Τιμή Επιστροφής

Ο αριθμός των σταλμένων byte.

## Socket::EndSend(System::SharedPtr\<IAsyncResult\>, SocketError\&) μέθοδος

Περιμένει μέχρι να ολοκληρωθεί η καθορισμένη ασύγχρονη λειτουργία αποστολής.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Ένα αντικείμενο [IAsyncResult](../../../system/iasyncresult/) που αντιπροσωπεύει μια ασύγχρονη λειτουργία αποστολής. |
| errorCode | [SocketError](../../socketerror/)\& | Η παράμετρος εξόδου όπου θα ανατεθεί ο κωδικός σφάλματος όταν η λειτουργία αποστολής αποτύχει. |

### Τιμή Επιστροφής

Ο αριθμός των σταλμένων byte.

## Δείτε επίσης

* Απαρίθμηση [SocketError](../../socketerror/)
* Τύπος ορισμού [SharedPtr](../../../system/sharedptr/)
* Κλάση [IAsyncResult](../../../system/iasyncresult/)
* Κλάση [Socket](../)
* Χώρος ονομάτων [System::Net::Sockets](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
---
title: EndReceive()
second_title: Aspose.Slides για την αναφορά API C++
description: Περιμένει μέχρι να ολοκληρωθεί η καθορισμένη ασύγχρονη λειτουργία λήψης.
type: docs
weight: 534
url: /el/system.net.sockets/socket/endreceive/
---
## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>) μέθοδος

Περιμένει μέχρι να ολοκληρωθεί η καθορισμένη ασύγχρονη λειτουργία λήψης.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | An [IAsyncResult](../../../system/iasyncresult/) object that represents an asynchronous receive operation. |

### Τιμή επιστροφής

Ο αριθμός των byte που λαμβάνονται.

## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>, SocketError\&) μέθοδος

Περιμένει μέχρι να ολοκληρωθεί η καθορισμένη ασύγχρονη λειτουργία λήψης.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | An [IAsyncResult](../../../system/iasyncresult/) object that represents an asynchronous receive operation. |
| errorCode | [SocketError](../../socketerror/)\& | The output parameter where the error code will be assigned when the receive operation fails. |

### Τιμή επιστροφής

Ο αριθμός των byte που λαμβάνονται.

## Δείτε επίσης

* Απαρίθμηση [SocketError](../../socketerror/)
* Τύπος ορισμού [SharedPtr](../../../system/sharedptr/)
* Κλάση [IAsyncResult](../../../system/iasyncresult/)
* Κλάση [Socket](../)
* Χώρος ονομάτων [System::Net::Sockets](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
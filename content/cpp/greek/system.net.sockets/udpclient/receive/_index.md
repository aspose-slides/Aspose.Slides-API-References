---
title: Receive()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει ένα datagram που στάλθηκε από διακομιστή.
type: docs
weight: 92
url: /el/system.net.sockets/udpclient/receive/
---
## UdpClient::Receive(System::SharedPtr\<IPEndPoint\>\&) μέθοδος


Επιστρέφει ένα datagram που στάλθηκε από διακομιστή.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::UdpClient::Receive(System::SharedPtr<IPEndPoint> &remoteEP)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\>\& | Ένα [IPEndPoint](../../../system.net/ipendpoint/) που αντιπροσωπεύει τον απομακρυσμένο κεντρικό υπολογιστή από τον οποίο εστάλησαν τα δεδομένα. |

### Τιμή Επιστροφής

Ένας πίνακας byte όπου τα ληφθέντα δεδομένα θα ανατεθούν.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IPEndPoint](../../../system.net/ipendpoint/)
* Κλάση [UdpClient](../)
* Χώρος ονομάτων [System::Net::Sockets](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
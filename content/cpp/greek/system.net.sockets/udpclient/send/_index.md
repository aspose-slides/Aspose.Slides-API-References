---
title: Send()
second_title: Αναφορά API του Aspose.Slides για C++
description: Στέλνει ένα πακέτο UDP προς τον κεντρικό υπολογιστή στο απομακρυσμένο σημείο τέλους.
type: docs
weight: 79
url: /el/system.net.sockets/udpclient/send/
---
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) μέθοδος

Στέλνει ένα πακέτο UDP προς τον κεντρικό υπολογιστή στο απομακρυσμένο σημείο τέλους.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, System::SharedPtr<IPEndPoint> endPoint)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ένας πίνακας τύπου [Byte](../../../system/byte/) για αποστολή |
| bytes | **int32_t** | Ο αριθμός των byte στο πακέτο. |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Ένα [IPEndPoint](../../../system.net/ipendpoint/) που αντιπροσωπεύει τον κεντρικό υπολογιστή και τη θύρα προς τα οποία θα αποσταλεί το πακέτο. |

### Τιμή Επιστροφής

Ο αριθμός των byte που αποστέλλονται.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) μέθοδος

Στέλνει ένα πακέτο UDP στη συγκεκριμένη θύρα του καθορισμένου απομακρυσμένου κεντρικού υπολογιστή.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, String hostname, int32_t port)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ένας πίνακας τύπου [Byte](../../../system/byte/) για αποστολή |
| bytes | **int32_t** | Ο αριθμός των byte στο πακέτο. |
| hostname | [String](../../../system/string/) | Ένα όνομα του απομακρυσμένου κεντρικού υπολογιστή. |
| port | **int32_t** | Ένας αριθμός απομακρυσμένης θύρας. |

### Τιμή Επιστροφής

Ο αριθμός των byte που αποστέλλονται.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t) μέθοδος

Στέλνει ένα πακέτο UDP σε έναν απομακρυσμένο κεντρικό υπολογιστή.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ένας πίνακας τύπου [Byte](../../../system/byte/) για αποστολή. |
| bytes | **int32_t** | Ο αριθμός των byte στο πακέτο. |

### Τιμή Επιστροφής

Ο αριθμός των byte που αποστέλλονται.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IPEndPoint](../../../system.net/ipendpoint/)
* Κλάση [UdpClient](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [System::Net::Sockets](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
---
title: Connect()
second_title: Αναφορά API Aspose.Slides για C++
description: Καθιερώνει μια σύνδεση στη καθορισμένη θύρα στον καθορισμένο κεντρικό υπολογιστή.
type: docs
weight: 66
url: /el/system.net.sockets/udpclient/connect/
---
## UdpClient::Connect(String, int32_t) μέθοδος

Καθιερώνει μια σύνδεση στην καθορισμένη θύρα στον καθορισμένο κεντρικό υπολογιστή.

```cpp
void System::Net::Sockets::UdpClient::Connect(String hostname, int32_t port)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Το όνομα του απομακρυσμένου DNS κεντρικού υπολογιστή στον οποίο πρόκειται να συνδεθείτε. |
| port | **int32_t** | Ο τοπικός αριθμός θύρας από τον οποίο πρόκειται να επικοινωνήσετε. |

## UdpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) μέθοδος

Καθιερώνει μια σύνδεση με τον κεντρικό υπολογιστή στη καθορισμένη διεύθυνση στην καθορισμένη θύρα.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPAddress> addr, int32_t port)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| addr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Η [IPAddress](../../../system.net/ipaddress/) του απομακρυσμένου κεντρικού υπολογιστή προς αποστολή δεδομένων. |
| port | **int32_t** | Ο τοπικός αριθμός θύρας από τον οποίο πρόκειται να επικοινωνήσετε. |

## UdpClient::Connect(System::SharedPtr\<IPEndPoint\>) μέθοδος

Καθιερώνει μια σύνδεση σε ένα απομακρυσμένο σημείο άκρου.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPEndPoint> endPoint)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | το σημείο άκρου στο οποίο δεσμεύετε τη σύνδεση UDP. |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [UdpClient](../)
* Κλάση [IPAddress](../../../system.net/ipaddress/)
* Κλάση [IPEndPoint](../../../system.net/ipendpoint/)
* Χώρος ονομάτων [System::Net::Sockets](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
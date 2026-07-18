---
title: Connect()
second_title: Aspose.Slides για C++ αναφορά API
description: Καθιερώνει σύνδεση με τον καθορισμένο απομακρυσμένο κεντρικό υπολογιστή.
type: docs
weight: 248
url: /el/system.net.sockets/tcpclient/connect/
---
## TcpClient::Connect(String, int32_t) μέθοδος

Καθιερώνει σύνδεση με τον καθορισμένο απομακρυσμένο κεντρικό υπολογιστή.

```cpp
void System::Net::Sockets::TcpClient::Connect(String hostname, int32_t port)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Ένα όνομα απομακρυσμένου κεντρικού υπολογιστή για σύνδεση. |
| port | **int32_t** | Μια θύρα του απομακρυσμένου κεντρικού υπολογιστή για σύνδεση. |

## TcpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) μέθοδος

Καθιερώνει σύνδεση με τον καθορισμένο απομακρυσμένο κεντρικό υπολογιστή.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Η διεύθυνση IP ενός απομακρυσμένου κεντρικού υπολογιστή. |
| port | **int32_t** | Μια θύρα του απομακρυσμένου κεντρικού υπολογιστή για σύνδεση. |

## TcpClient::Connect(System::SharedPtr\<IPEndPoint\>) μέθοδος

Καθιερώνει σύνδεση με τον καθορισμένο απομακρυσμένο κεντρικό υπολογιστή.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPEndPoint> remoteEP)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Ένας απομακρυσμένος κεντρικός υπολογιστής για σύνδεση. |

## TcpClient::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) μέθοδος

Καθιερώνει σύνδεση με τον καθορισμένο απομακρυσμένο κεντρικό υπολογιστή.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> ipAddresses, int32_t port)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ipAddresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Οι διευθύνσεις IP ενός απομακρυσμένου κεντρικού υπολογιστή. |
| port | **int32_t** | Μια θύρα του απομακρυσμένου κεντρικού υπολογιστή για σύνδεση. |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [TcpClient](../)
* Κλάση [IPAddress](../../../system.net/ipaddress/)
* Κλάση [IPEndPoint](../../../system.net/ipendpoint/)
* Χώρος ονομάτων [System::Net::Sockets](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
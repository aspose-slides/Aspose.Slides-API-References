---
title: Connect()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί μια σύνδεση με το καθορισμένο απομακρυσμένο σημείο άκρου.
type: docs
weight: 560
url: /el/system.net.sockets/socket/connect/
---
## Socket::Connect(System::SharedPtr\<EndPoint\>) μέθοδος

Δημιουργεί μια σύνδεση με το καθορισμένο απομακρυσμένο σημείο άκρου.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<EndPoint> remoteEP)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Το απομακρυσμένο σημείο άκρου. |

## Socket::Connect(System::SharedPtr\<IPAddress\>, int32_t) μέθοδος

Δημιουργεί μια σύνδεση με το καθορισμένο απομακρυσμένο σημείο άκρου.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Η διεύθυνση IP του απομακρυσμένου ξενιστή. |
| port | **int32_t** | Ο αριθμός θύρας του απομακρυσμένου ξενιστή. |

## Socket::Connect(String, int32_t) μέθοδος

Δημιουργεί μια σύνδεση με το καθορισμένο απομακρυσμένο σημείο άκρου.

```cpp
void System::Net::Sockets::Socket::Connect(String host, int32_t port)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| host | [String](../../../system/string/) | Το όνομα του απομακρυσμένου ξενιστή. |
| port | **int32_t** | Ο αριθμός θύρας του απομακρυσμένου ξενιστή. |

## Socket::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) μέθοδος

Δημιουργεί μια σύνδεση με το καθορισμένο απομακρυσμένο σημείο άκρου.

```cpp
void System::Net::Sockets::Socket::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Οι διευθύνσεις IP του απομακρυσμένου ξενιστή. |
| port | **int32_t** | Ο αριθμός θύρας του απομακρυσμένου ξενιστή. |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [EndPoint](../../../system.net/endpoint/)
* Κλάση [Socket](../)
* Κλάση [IPAddress](../../../system.net/ipaddress/)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [System::Net::Sockets](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
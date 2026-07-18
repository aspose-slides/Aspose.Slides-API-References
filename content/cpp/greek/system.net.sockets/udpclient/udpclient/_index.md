---
title: UdpClient()
second_title: Αναφορά API του Aspose.Slides για C++
description: Αρχικοποιεί μια νέα παρουσία της κλάσης UdpClient.
type: docs
weight: 27
url: /el/system.net.sockets/udpclient/udpclient/
---
## UdpClient::UdpClient() κατασκευαστής

Αρχικοποιεί μια νέα παρουσία της κλάσης [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient()
```

## UdpClient::UdpClient(AddressFamily) κατασκευαστής

Αρχικοποιεί μια νέα παρουσία της κλάσης [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(AddressFamily family)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | τιμή που καθορίζει το σχήμα διευθυνσιοδότησης του υποδοχέα. |

## UdpClient::UdpClient(int32_t) κατασκευαστής

Αρχικοποιεί μια νέα παρουσία της κλάσης [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| port | **int32_t** | ο τοπικός αριθμός θύρας από τον οποίο σκοπεύετε να επικοινωνήσετε. |

## UdpClient::UdpClient(int32_t, AddressFamily) κατασκευαστής

Αρχικοποιεί μια νέα παρουσία της κλάσης [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port, AddressFamily family)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| port | **int32_t** | ο τοπικός αριθμός θύρας από τον οποίο σκοπεύετε να επικοινωνήσετε. |
| family | [AddressFamily](../../addressfamily/) | τιμή που καθορίζει το σχήμα διευθυνσιοδότησης του υποδοχέα. |

## UdpClient::UdpClient(System::SharedPtr\<IPEndPoint\>) κατασκευαστής

Αρχικοποιεί μια νέα παρουσία της κλάσης [UdpClient](../). παράμετρος local EP το τοπικό σημείο τέλους στο οποίο δεσμεύετε τη σύνδεση UDP.

```cpp
System::Net::Sockets::UdpClient::UdpClient(System::SharedPtr<IPEndPoint> localEP)
```

## UdpClient::UdpClient(String, int32_t) κατασκευαστής

Δημιουργεί μια νέα παρουσία της κλάσης [UdpClient](../) και συνδέεται στον ορισμένο απομακρυσμένο κεντρικό υπολογιστή στη συγκεκριμένη θύρα.

```cpp
System::Net::Sockets::UdpClient::UdpClient(String hostname, int32_t port)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Το όνομα του απομακρυσμένου DNS κεντρικού υπολογιστή στον οποίο σκοπεύετε να συνδεθείτε. |
| port | **int32_t** | ο τοπικός αριθμός θύρας από τον οποίο σκοπεύετε να επικοινωνήσετε. |

## Δείτε επίσης

* Enum [AddressFamily](../../addressfamily/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [UdpClient](../)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [String](../../../system/string/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
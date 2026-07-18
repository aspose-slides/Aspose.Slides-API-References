---
title: NetworkStream()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα νέο στιγμιότυπο.
type: docs
weight: 170
url: /el/system.net.sockets/networkstream/networkstream/
---
## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>) Κατασκευαστής


Δημιουργεί ένα νέο στιγμιότυπο.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | Η υποδοχή που χρησιμοποιείται για αποστολή και λήψη δεδομένων. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, System::IO::FileAccess, bool) Κατασκευαστής


Δημιουργεί ένα νέο στιγμιότυπο.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, System::IO::FileAccess access, bool ownsSocket)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | Η υποδοχή που χρησιμοποιείται για αποστολή και λήψη δεδομένων. |
| access | [System::IO::FileAccess](../../../system.io/fileaccess/) | Καθορίζει τον τύπο πρόσβασης που δίνεται στο στιγμιότυπο μέσω της καθορισμένης υποδοχής. |
| ownsSocket | **bool** | Μια τιμή που υποδεικνύει εάν το τρέχον στιγμιότυπο αναλαμβάνει την ιδιοκτησία της καθορισμένης υποδοχής όταν η τιμή είναι true. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, bool) Κατασκευαστής


Δημιουργεί ένα νέο στιγμιότυπο.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, bool ownsSocket)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | Η υποδοχή που χρησιμοποιείται για αποστολή και λήψη δεδομένων. |
| ownsSocket | **bool** | Μια τιμή που υποδεικνύει εάν το τρέχον στιγμιότυπο αναλαμβάνει την ιδιοκτησία της καθορισμένης υποδοχής όταν η τιμή είναι true. |

## Δείτε επίσης

* Enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Socket](../../socket/)
* Κλάση [NetworkStream](../)
* Χώρος ονομάτων [System::Net::Sockets](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
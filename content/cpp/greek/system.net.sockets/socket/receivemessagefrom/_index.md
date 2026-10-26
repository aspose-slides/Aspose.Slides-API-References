---
title: ReceiveMessageFrom()
second_title: Aspose.Slides για C++ Αναφορά API
description: Λαμβάνει δεδομένα από το καθορισμένο σημείο τερματισμού και τα γράφει στον καθορισμένο πίνακα byte.
type: docs
weight: 677
url: /el/system.net.sockets/socket/receivemessagefrom/
---
## Socket::ReceiveMessageFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method


Λαμβάνει δεδομένα από το καθορισμένο σημείο τερματισμού και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ο πίνακας byte στον οποίο θα ανατεθούν τα ληφθέντα δεδομένα. |
| offset | **int32_t** | Η μετατόπιση σε byte στον καθορισμένο πίνακα. |
| size | **int32_t** | Ο αριθμός των byte που θα ληφθούν και θα ανατεθούν στον καθορισμένο πίνακα byte από το δείκτη «offset». |
| socketFlags | [SocketFlags](../../socketflags/)\& | Η συμπεριφορά λήψης. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Το απομακρυσμένο σημείο τερματισμού. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | Η παράμετρος εξόδου στην οποία θα ανατεθούν οι πληροφορίες σχετικά με το πακέτο. |

### Τιμή Επιστροφής

Ο αριθμός των ληφθέντων byte.

## Socket::ReceiveMessageFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method


Λαμβάνει δεδομένα από το καθορισμένο σημείο τερματισμού και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Ο πίνακας byte στον οποίο θα ανατεθούν τα ληφθέντα δεδομένα. |
| offset | **int32_t** | Η μετατόπιση σε byte στον καθορισμένο πίνακα. |
| size | **int32_t** | Ο αριθμός των byte που θα ληφθούν και θα ανατεθούν στον καθορισμένο πίνακα byte από το δείκτη «offset». |
| socketFlags | [SocketFlags](../../socketflags/)\& | Η συμπεριφορά λήψης. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Το απομακρυσμένο σημείο τερματισμού. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | Η παράμετρος εξόδου στην οποία θα ανατεθούν οι πληροφορίες σχετικά με το πακέτο. |

### Τιμή Επιστροφής

Ο αριθμός των ληφθέντων byte.

## Socket::ReceiveMessageFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method


Λαμβάνει δεδομένα από το καθορισμένο σημείο τερματισμού και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Ο πίνακας byte στον οποίο θα ανατεθούν τα ληφθέντα δεδομένα. |
| offset | **int32_t** | Η μετατόπιση σε byte στον καθορισμένο πίνακα. |
| size | **int32_t** | Ο αριθμός των byte που θα ληφθούν και θα ανατεθούν στον καθορισμένο πίνακα byte από το δείκτη «offset». |
| socketFlags | [SocketFlags](../../socketflags/)\& | Η συμπεριφορά λήψης. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Το απομακρυσμένο σημείο τερματισμού. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | Η παράμετρος εξόδου στην οποία θα ανατεθούν οι πληροφορίες σχετικά με το πακέτο. |

### Τιμή Επιστροφής

Ο αριθμός των ληφθέντων byte.

## Δείτε επίσης

* Απαρίθμηση [SocketFlags](../../socketflags/)
* Τυποορισμός [ArrayPtr](../../../system/arrayptr/)
* Τυποορισμός [SharedPtr](../../../system/sharedptr/)
* Κλάση [EndPoint](../../../system.net/endpoint/)
* Κλάση [IPPacketInformation](../../ippacketinformation/)
* Κλάση [Socket](../)
* Χώρος ονομάτων [System::Net::Sockets](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
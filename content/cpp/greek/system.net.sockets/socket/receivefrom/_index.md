---
title: ReceiveFrom()
second_title: Αναφορά API Aspose.Slides για C++
description: Λαμβάνει δεδομένα από το καθορισμένο σημείο άκρου και τα γράφει στον καθορισμένο πίνακα byte.
type: docs
weight: 690
url: /el/system.net.sockets/socket/receivefrom/
---
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) μέθοδος


Λαμβάνει δεδομένα από το καθορισμένο σημείο άκρου και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ο πίνακας byte στον οποίο θα ανατεθούν τα ληφθέντα δεδομένα. |
| offset | **int32_t** | Η μετατόπιση σε byte στον καθορισμένο πίνακα. |
| size | **int32_t** | Ο αριθμός των byte που θα ληφθούν και θα ανατεθούν στον καθορισμένο πίνακα byte από το δείκτη «offset». |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά λήψης. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Το απομακρυσμένο σημείο άκρου. |

### Τιμή Επιστροφής

Ο αριθμός των ληφθέντων byte.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) μέθοδος


Λαμβάνει δεδομένα από το καθορισμένο σημείο άκρου και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Ο πίνακας byte στον οποίο θα ανατεθούν τα ληφθέντα δεδομένα. |
| offset | **int32_t** | Η μετατόπιση σε byte στον καθορισμένο πίνακα. |
| size | **int32_t** | Ο αριθμός των byte που θα ληφθούν και θα ανατεθούν στον καθορισμένο πίνακα byte από το δείκτη «offset». |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά λήψης. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Το απομακρυσμένο σημείο άκρου. |

### Τιμή Επιστροφής

Ο αριθμός των ληφθέντων byte.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) μέθοδος


Λαμβάνει δεδομένα από το καθορισμένο σημείο άκρου και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Ο πίνακας byte στον οποίο θα ανατεθούν τα ληφθέντα δεδομένα. |
| offset | **int32_t** | Η μετατόπιση σε byte στον καθορισμένο πίνακα. |
| size | **int32_t** | Ο αριθμός των byte που θα ληφθούν και θα ανατεθούν στον καθορισμένο πίνακα byte από το δείκτη «offset». |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά λήψης. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Το απομακρυσμένο σημείο άκρου. |

### Τιμή Επιστροφής

Ο αριθμός των ληφθέντων byte.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) μέθοδος


Λαμβάνει δεδομένα από το καθορισμένο σημείο άκρου και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ο πίνακας byte στον οποίο θα ανατεθούν τα ληφθέντα δεδομένα. |
| size | **int32_t** | Ο αριθμός των byte που θα ληφθούν και θα ανατεθούν στον καθορισμένο πίνακα byte από το δείκτη «offset». |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά λήψης. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Το απομακρυσμένο σημείο άκρου. |

### Τιμή Επιστροφής

Ο αριθμός των ληφθέντων byte.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) μέθοδος


Λαμβάνει δεδομένα από το καθορισμένο σημείο άκρου και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Ο πίνακας byte στον οποίο θα ανατεθούν τα ληφθέντα δεδομένα. |
| size | **int32_t** | Ο αριθμός των byte που θα ληφθούν και θα ανατεθούν στον καθορισμένο πίνακα byte από το δείκτη «offset». |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά λήψης. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Το απομακρυσμένο σημείο άκρου. |

### Τιμή Επιστροφής

Ο αριθμός των ληφθέντων byte.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) μέθοδος


Λαμβάνει δεδομένα από το καθορισμένο σημείο άκρου και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Ο πίνακας byte στον οποίο θα ανατεθούν τα ληφθέντα δεδομένα. |
| size | **int32_t** | Ο αριθμός των byte που θα ληφθούν και θα ανατεθούν στον καθορισμένο πίνακα byte από το δείκτη «offset». |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά λήψης. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Το απομακρυσμένο σημείο άκρου. |

### Τιμή Επιστροφής

Ο αριθμός των ληφθέντων byte.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) μέθοδος


Λαμβάνει δεδομένα από το καθορισμένο σημείο άκρου και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ο πίνακας byte στον οποίο θα ανατεθούν τα ληφθέντα δεδομένα. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά λήψης. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Το απομακρυσμένο σημείο άκρου. |

### Τιμή Επιστροφής

Ο αριθμός των ληφθέντων byte.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) μέθοδος


Λαμβάνει δεδομένα από το καθορισμένο σημείο άκρου και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Ο πίνακας byte στον οποίο θα ανατεθούν τα ληφθέντα δεδομένα. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά λήψης. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Το απομακρυσμένο σημείο άκρου. |

### Τιμή Επιστροφής

Ο αριθμός των ληφθέντων byte.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) μέθοδος


Λαμβάνει δεδομένα από το καθορισμένο σημείο άκρου και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ο πίνακας byte στον οποίο θα ανατεθούν τα ληφθέντα δεδομένα. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά λήψης. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Το απομακρυσμένο σημείο άκρου. |

### Τιμή Επιστροφής

Ο αριθμός των ληφθέντων byte.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) μέθοδος


Λαμβάνει δεδομένα από το καθορισμένο σημείο άκρου και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ο πίνακας byte στον οποίο θα ανατεθούν τα ληφθέντα δεδομένα. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Το απομακρυσμένο σημείο άκρου. |

### Τιμή Επιστροφής

Ο αριθμός των ληφθέντων byte.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) μέθοδος


Λαμβάνει δεδομένα από το καθορισμένο σημείο άκρου και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Ο πίνακας byte στον οποίο θα ανατεθούν τα ληφθέντα δεδομένα. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Το απομακρυσμένο σημείο άκρου. |

### Τιμή Επιστροφής

Ο αριθμός των ληφθέντων byte.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>\&) μέθοδος


Λαμβάνει δεδομένα από το καθορισμένο σημείο άκρου και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> &remoteEP)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Ο πίνακας byte στον οποίο θα ανατεθούν τα ληφθέντα δεδομένα. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Το απομακρυσμένο σημείο άκρου. |

### Τιμή Επιστροφής

Ο αριθμός των ληφθέντων byte.

## Βλέπε επίσης

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [EndPoint](../../../system.net/endpoint/)
* Κλάση [Socket](../)
* Χώρος ονομάτων [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
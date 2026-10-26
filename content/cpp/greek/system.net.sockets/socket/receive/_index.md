---
title: Receive()
second_title: Aspose.Slides για C++ - Αναφορά API
description: Λαμβάνει δεδομένα από το socket και τα γράφει στον καθορισμένο πίνακα byte.
type: docs
weight: 664
url: /el/system.net.sockets/socket/receive/
---
## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) μέθοδος

Λαμβάνει δεδομένα από το socket και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Παράμετρος

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ο πίνακας byte όπου θα εκχωρηθούν τα ληφθέντα δεδομένα. |
| size | **int32_t** | Ο αριθμός των byte που θα ληφθούν. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά λήψης. |

### Τιμή Επιστροφής

Ο αριθμός των ληφθέντων byte.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) μέθοδος

Λαμβάνει δεδομένα από το socket και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Παράμετρος

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Ο πίνακας byte όπου θα εκχωρηθούν τα ληφθέντα δεδομένα. |
| size | **int32_t** | Ο αριθμός των byte που θα ληφθούν. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά λήψης. |

### Τιμή Επιστροφής

Ο αριθμός των ληφθέντων byte.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) μέθοδος

Λαμβάνει δεδομένα από το socket και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


### Παράμετρος

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Ο πίνακας byte όπου θα εκχωρηθούν τα ληφθέντα δεδομένα. |
| size | **int32_t** | Ο αριθμός των byte που θα ληφθούν. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά λήψης. |

### Τιμή Επιστροφής

Ο αριθμός των ληφθέντων byte.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, SocketFlags) μέθοδος

Λαμβάνει δεδομένα από το socket και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


### Παράμετρος

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ο πίνακας byte όπου θα εκχωρηθούν τα ληφθέντα δεδομένα. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά λήψης. |

### Τιμή Επιστροφής

Ο αριθμός των ληφθέντων byte.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, SocketFlags) μέθοδος

Λαμβάνει δεδομένα από το socket και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


### Παράμετρος

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Ο πίνακας byte όπου θα εκχωρηθούν τα ληφθέντα δεδομένα. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά λήψης. |

### Τιμή Επιστροφής

Ο αριθμός των ληφθέντων byte.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) μέθοδος

Λαμβάνει δεδομένα από το socket και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


### Παράμετρος

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Ο πίνακας byte όπου θα εκχωρηθούν τα ληφθέντα δεδομένα. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά λήψης. |

### Τιμή Επιστροφής

Ο αριθμός των ληφθέντων byte.

## Socket::Receive(System::ArrayPtr\<uint8_t\>) μέθοδος

Λαμβάνει δεδομένα από το socket και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer)
```


### Παράμετρος

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ο πίνακας byte όπου θα εκχωρηθούν τα ληφθέντα δεδομένα. |

### Τιμή Επιστροφής

Ο αριθμός των ληφθέντων byte.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>) μέθοδος

Λαμβάνει δεδομένα από το socket και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer)
```


### Παράμετρος

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Ο πίνακας byte όπου θα εκχωρηθούν τα ληφθέντα δεδομένα. |

### Τιμή Επιστροφής

Ο αριθμός των ληφθέντων byte.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&) μέθοδος

Λαμβάνει δεδομένα από το socket και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer)
```


### Παράμετρος

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Ο πίνακας byte όπου θα εκχωρηθούν τα ληφθέντα δεδομένα. |

### Τιμή Επιστροφής

Ο αριθμός των ληφθέντων byte.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) μέθοδος

Λαμβάνει δεδομένα από το socket και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Παράμετρος

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ο πίνακας byte όπου θα εκχωρηθούν τα ληφθέντα δεδομένα. |
| offset | **int32_t** | Η μετατόπιση σε byte στον καθορισμένο πίνακα. |
| size | **int32_t** | Ο αριθμός των byte που θα ληφθούν και θα εκχωρηθούν στον πίνακα byte από τη θέση «offset». |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά λήψης. |

### Τιμή Επιστροφής

Ο αριθμός των ληφθέντων byte.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) μέθοδος

Λαμβάνει δεδομένα από το socket και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Παράμετρος

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Ο πίνακας byte όπου θα εκχωρηθούν τα ληφθέντα δεδομένα. |
| offset | **int32_t** | Η μετατόπιση σε byte στον καθορισμένο πίνακα. |
| size | **int32_t** | Ο αριθμός των byte που θα ληφθούν και θα εκχωρηθούν στον πίνακα byte από τη θέση «offset». |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά λήψης. |

### Τιμή Επιστροφής

Ο αριθμός των ληφθέντων byte.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) μέθοδος

Λαμβάνει δεδομένα από το socket και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Παράμετρος

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Ο πίνακας byte όπου θα εκχωρηθούν τα ληφθέντα δεδομένα. |
| offset | **int32_t** | Η μετατόπιση σε byte στον καθορισμένο πίνακα. |
| size | **int32_t** | Ο αριθμός των byte που θα ληφθούν και θα εκχωρηθούν στον πίνακα byte από τη θέση «offset». |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά λήψης. |

### Τιμή Επιστροφής

Ο αριθμός των ληφθέντων byte.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) μέθοδος

Λαμβάνει δεδομένα από το socket και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Παράμετρος

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ο πίνακας byte όπου θα εκχωρηθούν τα ληφθέντα δεδομένα. |
| offset | **int32_t** | Η μετατόπιση σε byte στον καθορισμένο πίνακα. |
| size | **int32_t** | Ο αριθμός των byte που θα ληφθούν και θα εκχωρηθούν στον πίνακα byte από τη θέση «offset». |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά λήψης. |
| errorCode | [SocketError](../../socketerror/)\& | Η παράμετρος εξόδου όπου θα εκχωρηθεί ο κωδικός σφάλματος όταν η λειτουργία λήψης αποτύχει. |

### Τιμή Επιστροφής

Ο αριθμός των ληφθέντων byte.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) μέθοδος

Λαμβάνει δεδομένα από το socket και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Παράμετρος

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Ο πίνακας byte όπου θα εκχωρηθούν τα ληφθέντα δεδομένα. |
| offset | **int32_t** | Η μετατόπιση σε byte στον καθορισμένο πίνακα. |
| size | **int32_t** | Ο αριθμός των byte που θα ληφθούν και θα εκχωρηθούν στον πίνακα byte από τη θέση «offset». |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά λήψης. |
| errorCode | [SocketError](../../socketerror/)\& | Η παράμετρος εξόδου όπου θα εκχωρηθεί ο κωδικός σφάλματος όταν η λειτουργία λήψης αποτύχει. |

### Τιμή Επιστροφής

Ο αριθμός των ληφθέντων byte.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) μέθοδος

Λαμβάνει δεδομένα από το socket και τα γράφει στον καθορισμένο πίνακα byte.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Παράμετρος

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Ο πίνακας byte όπου θα εκχωρηθούν τα ληφθέντα δεδομένα. |
| offset | **int32_t** | Η μετατόπιση σε byte στον καθορισμένο πίνακα. |
| size | **int32_t** | Ο αριθμός των byte που θα ληφθούν και θα εκχωρηθούν στον πίνακα byte από τη θέση «offset». |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά λήψης. |
| errorCode | [SocketError](../../socketerror/)\& | Η παράμετρος εξόδου όπου θα εκχωρηθεί ο κωδικός σφάλματος όταν η λειτουργία λήψης αποτύχει. |

### Τιμή Επιστροφής

Ο αριθμός των ληφθέντων byte.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) μέθοδος

Λαμβάνει δεδομένα από το socket και τα γράφει στους καθορισμένους πίνακες byte.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


### Παράμετρος

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Οι πίνακες byte όπου θα εκχωρηθούν τα ληφθέντα δεδομένα. |

### Τιμή Επιστροφής

Ο αριθμός των byte που λήφθηκαν.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) μέθοδος

Λαμβάνει δεδομένα από το socket και τα γράφει στους καθορισμένους πίνακες byte.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


### Παράμετρος

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Οι πίνακες byte όπου θα εκχωρηθούν τα ληφθέντα δεδομένα. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά λήψης. |

### Τιμή Επιστροφής

Ο αριθμός των ληφθέντων byte.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) μέθοδος

Λαμβάνει δεδομένα από το socket και τα γράφει στους καθορισμένους πίνακες byte.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


### Παράμετρος

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Οι πίνακες byte όπου θα εκχωρηθούν τα ληφθέντα δεδομένα. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά λήψης. |
| errorCode | [SocketError](../../socketerror/)\& | Η παράμετρος εξόδου όπου θα εκχωρηθεί ο κωδικός σφάλματος όταν η λειτουργία λήψης αποτύχει. |

### Τιμή Επιστροφής

Ο αριθμός των ληφθέντων byte.

## Δείτε επίσης

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
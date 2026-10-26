---
title: Send()
second_title: Αναφορά API του Aspose.Slides για C++
description: Αποστέλλει τα καθορισμένα δεδομένα στη υποδοχή.
type: docs
weight: 638
url: /el/system.net.sockets/socket/send/
---
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) μέθοδος

Αποστέλλει τα καθορισμένα δεδομένα στη υποδοχή.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Τα δεδομένα προς αποστολή. |
| size | **int32_t** | Ο αριθμός των byte από τα καθορισμένα δεδομένα που πρέπει να σταλεί. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά αποστολής. |

### Τιμή Επιστροφής

Ο αριθμός των σταλμένων byte.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) μέθοδος

Αποστέλλει τα καθορισμένα δεδομένα στη υποδοχή.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Τα δεδομένα προς αποστολή. |
| size | **int32_t** | Ο αριθμός των byte από τα καθορισμένα δεδομένα που πρέπει να σταλεί. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά αποστολής. |

### Τιμή Επιστροφής

Ο αριθμός των σταλμένων byte.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) μέθοδος

Αποστέλλει τα καθορισμένα δεδομένα στη υποδοχή.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Τα δεδομένα προς αποστολή. |
| size | **int32_t** | Ο αριθμός των byte από τα καθορισμένα δεδομένα που πρέπει να σταλεί. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά αποστολής. |

### Τιμή Επιστροφής

Ο αριθμός των σταλμένων byte.

## Socket::Send(System::ArrayPtr\<uint8_t\>, SocketFlags) μέθοδος

Αποστέλλει τα καθορισμένα δεδομένα στη υποδοχή.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Τα δεδομένα προς αποστολή. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά αποστολής. |

### Τιμή Επιστροφής

Ο αριθμός των σταλμένων byte.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, SocketFlags) μέθοδος

Αποστέλλει τα καθορισμένα δεδομένα στη υποδοχή.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Τα δεδομένα προς αποστολή. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά αποστολής. |

### Τιμή Επιστροφής

Ο αριθμός των σταλμένων byte.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) μέθοδος

Αποστέλλει τα καθορισμένα δεδομένα στη υποδοχή.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Τα δεδομένα προς αποστολή. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά αποστολής. |

### Τιμή Επιστροφής

Ο αριθμός των σταλμένων byte.

## Socket::Send(System::ArrayPtr\<uint8_t\>) μέθοδος

Αποστέλλει τα καθορισμένα δεδομένα στη υποδοχή.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Τα δεδομένα προς αποστολή. |

### Τιμή Επιστροφής

Ο αριθμός των σταλμένων byte.

## Socket::Send(System::Details::ArrayView\<uint8_t\>) μέθοδος

Αποστέλλει τα καθορισμένα δεδομένα στη υποδοχή.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Τα δεδομένα προς αποστολή. |

### Τιμή Επιστροφής

Ο αριθμός των σταλμένων byte.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&) μέθοδος

Αποστέλλει τα καθορισμένα δεδομένα στη υποδοχή.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Τα δεδομένα προς αποστολή. |

### Τιμή Επιστροφής

Ο αριθμός των σταλμένων byte.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) μέθοδος

Αποστέλλει τα καθορισμένα δεδομένα στη υποδοχή.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Συλλογή πινάκων byte από τα οποία πρέπει να σταλούν δεδομένα. |

### Τιμή Επιστροφής

Ο αριθμός των σταλμένων byte.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) μέθοδος

Αποστέλλει τα καθορισμένα δεδομένα στη υποδοχή.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Συλλογή πινάκων byte από τα οποία πρέπει να σταλούν δεδομένα. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά αποστολής. |

### Τιμή Επιστροφής

Ο αριθμός των σταλμένων byte.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) μέθοδος

Αποστέλλει τα καθορισμένα δεδομένα στη υποδοχή.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Συλλογή πινάκων byte από τα οποία πρέπει να σταλούν δεδομένα. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά αποστολής. |
| errorCode | [SocketError](../../socketerror/)\& | Η παράμετρος εξόδου όπου ο κωδικός σφάλματος θα αντιστοιχιστεί όταν η λειτουργία αποστολής αποτύχει. |

### Τιμή Επιστροφής

Ο αριθμός των σταλμένων byte.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) μέθοδος

Αποστέλλει τα καθορισμένα δεδομένα στη υποδοχή.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Τα δεδομένα προς αποστολή. |
| offset | **int32_t** | Η μετατόπιση σε byte στον καθορισμένο πίνακα. |
| size | **int32_t** | Ο αριθμός των byte στον καθορισμένο πίνακα που ξεκινούν από την παράμετρο 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά αποστολής. |

### Τιμή Επιστροφής

Ο αριθμός των σταλμένων byte.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) μέθοδος

Αποστέλλει τα καθορισμένα δεδομένα στη υποδοχή.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Τα δεδομένα προς αποστολή. |
| offset | **int32_t** | Η μετατόπιση σε byte στον καθορισμένο πίνακα. |
| size | **int32_t** | Ο αριθμός των byte στον καθορισμένο πίνακα που ξεκινούν από την παράμετρο 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά αποστολής. |

### Τιμή Επιστροφής

Ο αριθμός των σταλμένων byte.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) μέθοδος

Αποστέλλει τα καθορισμένα δεδομένα στη υποδοχή.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Τα δεδομένα προς αποστολή. |
| offset | **int32_t** | Η μετατόπιση σε byte στον καθορισμένο πίνακα. |
| size | **int32_t** | Ο αριθμός των byte στον καθορισμένο πίνακα που ξεκινούν από την παράμετρο 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά αποστολής. |

### Τιμή Επιστροφής

Ο αριθμός των σταλμένων byte.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) μέθοδος

Αποστέλλει τα καθορισμένα δεδομένα στη υποδοχή.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Τα δεδομένα προς αποστολή. |
| offset | **int32_t** | Η μετατόπιση σε byte στον καθορισμένο πίνακα. |
| size | **int32_t** | Ο αριθμός των byte στον καθορισμένο πίνακα που ξεκινούν από την παράμετρο 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά αποστολής. |
| errorCode | [SocketError](../../socketerror/)\& | Η παράμετρος εξόδου όπου ο κωδικός σφάλματος θα αντιστοιχιστεί όταν η λειτουργία αποστολής αποτύχει. |

### Τιμή Επιστροφής

Ο αριθμός των σταλμένων byte.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) μέθοδος

Αποστέλλει τα καθορισμένα δεδομένα στη υποδοχή.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Τα δεδομένα προς αποστολή. |
| offset | **int32_t** | Η μετατόπιση σε byte στον καθορισμένο πίνακα. |
| size | **int32_t** | Ο αριθμός των byte στον καθορισμένο πίνακα που ξεκινούν από την παράμετρο 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά αποστολής. |
| errorCode | [SocketError](../../socketerror/)\& | Η παράμετρος εξόδου όπου ο κωδικός σφάλματος θα αντιστοιχιστεί όταν η λειτουργία αποστολής αποτύχει. |

### Τιμή Επιστροφής

Ο αριθμός των σταλμένων byte.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) μέθοδος

Αποστέλλει τα καθορισμένα δεδομένα στη υποδοχή.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Τα δεδομένα προς αποστολή. |
| offset | **int32_t** | Η μετατόπιση σε byte στον καθορισμένο πίνακα. |
| size | **int32_t** | Ο αριθμός των byte στον καθορισμένο πίνακα που ξεκινούν από την παράμετρο 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά αποστολής. |
| errorCode | [SocketError](../../socketerror/)\& | Η παράμετρος εξόδου όπου ο κωδικός σφάλματος θα αντιστοιχιστεί όταν η λειτουργία αποστολής αποτύχει. |

### Τιμή Επιστροφής

Ο αριθμός των σταλμένων byte.

## Δείτε επίσης

* Απαρίθμηση [SocketFlags](../../socketflags/)
* Απαρίθμηση [SocketError](../../socketerror/)
* Ορισμός τύπου [ArrayPtr](../../../system/arrayptr/)
* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [Socket](../)
* Κλάση [IList](../../../system.collections.generic/ilist/)
* Κλάση [ArraySegment](../../../system/arraysegment/)
* Χώρος ονομάτων [System::Net::Sockets](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
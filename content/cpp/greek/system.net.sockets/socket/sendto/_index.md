---
title: SendTo()
second_title: Αναφορά API Aspose.Slides για C++
description: Στέλνει τα καθορισμένα δεδομένα στο καθορισμένο σημείο τερματισμού.
type: docs
weight: 651
url: /el/system.net.sockets/socket/sendto/
---
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) μέθοδος


Στέλνει τα καθορισμένα δεδομένα στο καθορισμένο σημείο τερματισμού.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Τα δεδομένα προς αποστολή. |
| offset | **int32_t** | Η μετατόπιση σε bytes στον καθορισμένο πίνακα. |
| size | **int32_t** | Ο αριθμός των bytes στον καθορισμένο πίνακα που ξεκινά από την παράμετρο 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά αποστολής. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Το απομακρυσμένο σημείο τερματισμού. |

### Τιμή Επιστροφής

Ο αριθμός των σταλμένων bytes.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) μέθοδος


Στέλνει τα καθορισμένα δεδομένα στο καθορισμένο σημείο τερματισμού.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Τα δεδομένα προς αποστολή. |
| offset | **int32_t** | Η μετατόπιση σε bytes στον καθορισμένο πίνακα. |
| size | **int32_t** | Ο αριθμός των bytes στον καθορισμένο πίνακα που ξεκινά από την παράμετρο 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά αποστολής. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Το απομακρυσμένο σημείο τερματισμού. |

### Τιμή Επιστροφής

Ο αριθμός των σταλμένων bytes.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) μέθοδος


Στέλνει τα καθορισμένα δεδομένα στο καθορισμένο σημείο τερματισμού.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Τα δεδομένα προς αποστολή. |
| offset | **int32_t** | Η μετατόπιση σε bytes στον καθορισμένο πίνακα. |
| size | **int32_t** | Ο αριθμός των bytes στον καθορισμένο πίνακα που ξεκινά από την παράμετρο 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά αποστολής. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Το απομακρυσμένο σημείο τερματισμού. |

### Τιμή Επιστροφής

Ο αριθμός των σταλμένων bytes.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) μέθοδος


Στέλνει τα καθορισμένα δεδομένα στο καθορισμένο σημείο τερματισμού.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Τα δεδομένα προς αποστολή. |
| size | **int32_t** | Ο αριθμός των bytes στον καθορισμένο πίνακα. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά αποστολής. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Το απομακρυσμένο σημείο τερματισμού. |

### Τιμή Επιστροφής

Ο αριθμός των σταλμένων bytes.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) μέθοδος


Στέλνει τα καθορισμένα δεδομένα στο καθορισμένο σημείο τερματισμού.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Τα δεδομένα προς αποστολή. |
| size | **int32_t** | Ο αριθμός των bytes στον καθορισμένο πίνακα. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά αποστολής. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Το απομακρυσμένο σημείο τερματισμού. |

### Τιμή Επιστροφής

Ο αριθμός των σταλμένων bytes.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) μέθοδος


Στέλνει τα καθορισμένα δεδομένα στο καθορισμένο σημείο τερματισμού.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Τα δεδομένα προς αποστολή. |
| size | **int32_t** | Ο αριθμός των bytes στον καθορισμένο πίνακα. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά αποστολής. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Το απομακρυσμένο σημείο τερματισμού. |

### Τιμή Επιστροφής

Ο αριθμός των σταλμένων bytes.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) μέθοδος


Στέλνει τα καθορισμένα δεδομένα στο καθορισμένο σημείο τερματισμού.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Τα δεδομένα προς αποστολή. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά αποστολής. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Το απομακρυσμένο σημείο τερματισμού. |

### Τιμή Επιστροφής

Ο αριθμός των σταλμένων bytes.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) μέθοδος


Στέλνει τα καθορισμένα δεδομένα στο καθορισμένο σημείο τερματισμού.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Τα δεδομένα προς αποστολή. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά αποστολής. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Το απομακρυσμένο σημείο τερματισμού. |

### Τιμή Επιστροφής

Ο αριθμός των σταλμένων bytes.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags, System::SharedPtr\<EndPoint\>) μέθοδος


Στέλνει τα καθορισμένα δεδομένα στο καθορισμένο σημείο τερματισμού.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Τα δεδομένα προς αποστολή. |
| socketFlags | [SocketFlags](../../socketflags/) | Η συμπεριφορά αποστολής. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Το απομακρυσμένο σημείο τερματισμού. |

### Τιμή Επιστροφής

Ο αριθμός των σταλμένων bytes.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>) μέθοδος


Στέλνει τα καθορισμένα δεδομένα στο καθορισμένο σημείο τερματισμού.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Τα δεδομένα προς αποστολή. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Το απομακρυσμένο σημείο τερματισμού. |

### Τιμή Επιστροφής

Ο αριθμός των σταλμένων bytes.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>) μέθοδος


Στέλνει τα καθορισμένα δεδομένα στο καθορισμένο σημείο τερματισμού.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Τα δεδομένα προς αποστολή. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Το απομακρυσμένο σημείο τερματισμού. |

### Τιμή Επιστροφής

Ο αριθμός των σταλμένων bytes.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>) μέθοδος


Στέλνει τα καθορισμένα δεδομένα στο καθορισμένο σημείο τερματισμού.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> remoteEP)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Τα δεδομένα προς αποστολή. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Το απομακρυσμένο σημείο τερματισμού. |

### Τιμή Επιστροφής

Ο αριθμός των σταλμένων bytes.

## Δείτε επίσης

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
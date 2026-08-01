---
title: Receive()
second_title: Aspose.Slides voor C++ API-referentie
description: Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-array.
type: docs
weight: 664
url: /nl/system.net.sockets/socket/receive/
---
## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) method

Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-array.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De byte-array waarin de ontvangen gegevens worden toegewezen. |
| size | **int32_t** | Het aantal bytes om te ontvangen. |
| socketFlags | [SocketFlags](../../socketflags/) | Het ontvangsgedrag. |

### Retourwaarde

Het aantal ontvangen bytes.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) method

Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-array.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | De byte-array waarin de ontvangen gegevens worden toegewezen. |
| size | **int32_t** | Het aantal bytes om te ontvangen. |
| socketFlags | [SocketFlags](../../socketflags/) | Het ontvangsgedrag. |

### Retourwaarde

Het aantal ontvangen bytes.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) method

Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-array.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | De byte-array waarin de ontvangen gegevens worden toegewezen. |
| size | **int32_t** | Het aantal bytes om te ontvangen. |
| socketFlags | [SocketFlags](../../socketflags/) | Het ontvangsgedrag. |

### Retourwaarde

Het aantal ontvangen bytes.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, SocketFlags) method

Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-array.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De byte-array waarin de ontvangen gegevens worden toegewezen. |
| socketFlags | [SocketFlags](../../socketflags/) | Het ontvangsgedrag. |

### Retourwaarde

Het aantal ontvangen bytes.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, SocketFlags) method

Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-array.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | De byte-array waarin de ontvangen gegevens worden toegewezen. |
| socketFlags | [SocketFlags](../../socketflags/) | Het ontvangsgedrag. |

### Retourwaarde

Het aantal ontvangen bytes.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) method

Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-array.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | De byte-array waarin de ontvangen gegevens worden toegewezen. |
| socketFlags | [SocketFlags](../../socketflags/) | Het ontvangsgedrag. |

### Retourwaarde

Het aantal ontvangen bytes.

## Socket::Receive(System::ArrayPtr\<uint8_t\>) method

Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-array.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De byte-array waarin de ontvangen gegevens worden toegewezen. |

### Retourwaarde

Het aantal ontvangen bytes.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>) method

Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-array.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | De byte-array waarin de ontvangen gegevens worden toegewezen. |

### Retourwaarde

Het aantal ontvangen bytes.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&) method

Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-array.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | De byte-array waarin de ontvangen gegevens worden toegewezen. |

### Retourwaarde

Het aantal ontvangen bytes.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) method

Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-array.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De byte-array waarin de ontvangen gegevens worden toegewezen. |
| offset | **int32_t** | De offset in bytes in de opgegeven array. |
| size | **int32_t** | Het aantal bytes om te ontvangen dat wordt toegewezen aan de opgegeven byte-array vanaf de 'offset'-index. |
| socketFlags | [SocketFlags](../../socketflags/) | Het ontvangsgedrag. |

### Retourwaarde

Het aantal ontvangen bytes.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) method

Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-array.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | De byte-array waarin de ontvangen gegevens worden toegewezen. |
| offset | **int32_t** | De offset in bytes in de opgegeven array. |
| size | **int32_t** | Het aantal bytes om te ontvangen dat wordt toegewezen aan de opgegeven byte-array vanaf de 'offset'-index. |
| socketFlags | [SocketFlags](../../socketflags/) | Het ontvangsgedrag. |

### Retourwaarde

Het aantal ontvangen bytes.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) method

Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-array.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | De byte-array waarin de ontvangen gegevens worden toegewezen. |
| offset | **int32_t** | De offset in bytes in de opgegeven array. |
| size | **int32_t** | Het aantal bytes om te ontvangen dat wordt toegewezen aan de opgegeven byte-array vanaf de 'offset'-index. |
| socketFlags | [SocketFlags](../../socketflags/) | Het ontvangsgedrag. |

### Retourwaarde

Het aantal ontvangen bytes.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method

Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-array.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De byte-array waarin de ontvangen gegevens worden toegewezen. |
| offset | **int32_t** | De offset in bytes in de opgegeven array. |
| size | **int32_t** | Het aantal bytes om te ontvangen dat wordt toegewezen aan de opgegeven byte-array vanaf de 'offset'-index. |
| socketFlags | [SocketFlags](../../socketflags/) | Het ontvangsgedrag. |
| errorCode | [SocketError](../../socketerror/)\& | De uitvoerparameter waarin de foutcode wordt toegewezen wanneer de ontvangstaak mislukt. |

### Retourwaarde

Het aantal ontvangen bytes.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method

Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-array.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | De byte-array waarin de ontvangen gegevens worden toegewezen. |
| offset | **int32_t** | De offset in bytes in de opgegeven array. |
| size | **int32_t** | Het aantal bytes om te ontvangen dat wordt toegewezen aan de opgegeven byte-array vanaf de 'offset'-index. |
| socketFlags | [SocketFlags](../../socketflags/) | Het ontvangsgedrag. |
| errorCode | [SocketError](../../socketerror/)\& | De uitvoerparameter waarin de foutcode wordt toegewezen wanneer de ontvangstaak mislukt. |

### Retourwaarde

Het aantal ontvangen bytes.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) method

Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-array.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | De byte-array waarin de ontvangen gegevens worden toegewezen. |
| offset | **int32_t** | De offset in bytes in de opgegeven array. |
| size | **int32_t** | Het aantal bytes om te ontvangen dat wordt toegewezen aan de opgegeven byte-array vanaf de 'offset'-index. |
| socketFlags | [SocketFlags](../../socketflags/) | Het ontvangsgedrag. |
| errorCode | [SocketError](../../socketerror/)\& | De uitvoerparameter waarin de foutcode wordt toegewezen wanneer de ontvangstaak mislukt. |

### Retourwaarde

Het aantal ontvangen bytes.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) method

Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-arrays.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | De byte-arrays waarin de ontvangen gegevens worden toegewezen. |

### Retourwaarde

Het aantal bytes dat wordt ontvangen.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) method

Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-arrays.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | De byte-arrays waarin de ontvangen gegevens worden toegewezen. |
| socketFlags | [SocketFlags](../../socketflags/) | Het ontvangsgedrag. |

### Retourwaarde

Het aantal ontvangen bytes.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) method

Ontvangt gegevens van de socket en schrijft deze naar de opgegeven byte-arrays.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | De byte-arrays waarin de ontvangen gegevens worden toegewezen. |
| socketFlags | [SocketFlags](../../socketflags/) | Het ontvangsgedrag. |
| errorCode | [SocketError](../../socketerror/)\& | De uitvoerparameter waarin de foutcode wordt toegewezen wanneer de ontvangstaak mislukt. |

### Retourwaarde

Het aantal ontvangen bytes.

## Zie ook

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
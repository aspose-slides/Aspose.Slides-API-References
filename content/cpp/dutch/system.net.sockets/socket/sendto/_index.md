---
title: SendTo()
second_title: Aspose.Slides voor C++ API-referentie
description: Stuurt de opgegeven gegevens naar het opgegeven eindpunt.
type: docs
weight: 651
url: /nl/system.net.sockets/socket/sendto/
---
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) methode

Stuurt de opgegeven gegevens naar het opgegeven eindpunt.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De te verzenden gegevens. |
| offset | **int32_t** | De offset in bytes in de opgegeven array. |
| size | **int32_t** | Het aantal bytes in de opgegeven array beginnend bij de parameter 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Het verzendgedrag. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Het externe eindpunt. |

### Retourwaarde

Het aantal verzonden bytes.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) methode


Stuurt de opgegeven gegevens naar het opgegeven eindpunt.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | De te verzenden gegevens. |
| offset | **int32_t** | De offset in bytes in de opgegeven array. |
| size | **int32_t** | Het aantal bytes in de opgegeven array beginnend bij de parameter 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Het verzendgedrag. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Het externe eindpunt. |

### Retourwaarde

Het aantal verzonden bytes.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) methode


Stuurt de opgegeven gegevens naar het opgegeven eindpunt.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | De te verzenden gegevens. |
| offset | **int32_t** | De offset in bytes in de opgegeven array. |
| size | **int32_t** | Het aantal bytes in de opgegeven array beginnend bij de parameter 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Het verzendgedrag. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Het externe eindpunt. |

### Retourwaarde

Het aantal verzonden bytes.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) methode


Stuurt de opgegeven gegevens naar het opgegeven eindpunt.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De te verzenden gegevens. |
| size | **int32_t** | Het aantal bytes in de opgegeven array. |
| socketFlags | [SocketFlags](../../socketflags/) | Het verzendgedrag. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Het externe eindpunt. |

### Retourwaarde

Het aantal verzonden bytes.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) methode


Stuurt de opgegeven gegevens naar het opgegeven eindpunt.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | De te verzenden gegevens. |
| size | **int32_t** | Het aantal bytes in de opgegeven array. |
| socketFlags | [SocketFlags](../../socketflags/) | Het verzendgedrag. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Het externe eindpunt. |

### Retourwaarde

Het aantal verzonden bytes.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) methode


Stuurt de opgegeven gegevens naar het opgegeven eindpunt.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | De te verzenden gegevens. |
| size | **int32_t** | Het aantal bytes in de opgegeven array. |
| socketFlags | [SocketFlags](../../socketflags/) | Het verzendgedrag. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Het externe eindpunt. |

### Retourwaarde

Het aantal verzonden bytes.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) methode


Stuurt de opgegeven gegevens naar het opgegeven eindpunt.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De te verzenden gegevens. |
| socketFlags | [SocketFlags](../../socketflags/) | Het verzendgedrag. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Het externe eindpunt. |

### Retourwaarde

Het aantal verzonden bytes.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) methode


Stuurt de opgegeven gegevens naar het opgegeven eindpunt.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | De te verzenden gegevens. |
| socketFlags | [SocketFlags](../../socketflags/) | Het verzendgedrag. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Het externe eindpunt. |

### Retourwaarde

Het aantal verzonden bytes.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags, System::SharedPtr\<EndPoint\>) methode


Stuurt de opgegeven gegevens naar het opgegeven eindpunt.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | De te verzenden gegevens. |
| socketFlags | [SocketFlags](../../socketflags/) | Het verzendgedrag. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Het externe eindpunt. |

### Retourwaarde

Het aantal verzonden bytes.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>) methode


Stuurt de opgegeven gegevens naar het opgegeven eindpunt.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De te verzenden gegevens. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Het externe eindpunt. |

### Retourwaarde

Het aantal verzonden bytes.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>) methode


Stuurt de opgegeven gegevens naar het opgegeven eindpunt.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | De te verzenden gegevens. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Het externe eindpunt. |

### Retourwaarde

Het aantal verzonden bytes.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>) methode


Stuurt de opgegeven gegevens naar het opgegeven eindpunt.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> remoteEP)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | De te verzenden gegevens. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Het externe eindpunt. |

### Retourwaarde

Het aantal verzonden bytes.

## Zie ook

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
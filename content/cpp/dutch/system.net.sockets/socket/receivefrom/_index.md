---
title: ReceiveFrom()
second_title: Aspose.Slides voor C++ API-referentie
description: Ontvangt gegevens van het opgegeven eindpunt en schrijft ze naar de opgegeven byte-array.
type: docs
weight: 690
url: /nl/system.net.sockets/socket/receivefrom/
---
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Ontvangt gegevens van het opgegeven eindpunt en schrijft ze naar de opgegeven byte-array.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De byte-array waar de ontvangen gegevens aan worden toegewezen. |
| offset | **int32_t** | De offset in bytes in de opgegeven array. |
| size | **int32_t** | Het aantal bytes dat moet worden ontvangen en dat aan de opgegeven byte-array wordt toegewezen vanaf de 'offset'-index. |
| socketFlags | [SocketFlags](../../socketflags/) | Het ontvangstgedrag. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Het externe eindpunt. |

### Retourwaarde

Het aantal ontvangen bytes.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Ontvangt gegevens van het opgegeven eindpunt en schrijft ze naar de opgegeven byte-array.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | De byte-array waar de ontvangen gegevens aan worden toegewezen. |
| offset | **int32_t** | De offset in bytes in de opgegeven array. |
| size | **int32_t** | Het aantal bytes dat moet worden ontvangen en dat aan de opgegeven byte-array wordt toegewezen vanaf de 'offset'-index. |
| socketFlags | [SocketFlags](../../socketflags/) | Het ontvangstgedrag. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Het externe eindpunt. |

### Retourwaarde

Het aantal ontvangen bytes.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Ontvangt gegevens van het opgegeven eindpunt en schrijft ze naar de opgegeven byte-array.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | De byte-array waar de ontvangen gegevens aan worden toegewezen. |
| offset | **int32_t** | De offset in bytes in de opgegeven array. |
| size | **int32_t** | Het aantal bytes dat moet worden ontvangen en dat aan de opgegeven byte-array wordt toegewezen vanaf de 'offset'-index. |
| socketFlags | [SocketFlags](../../socketflags/) | Het ontvangstgedrag. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Het externe eindpunt. |

### Retourwaarde

Het aantal ontvangen bytes.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Ontvangt gegevens van het opgegeven eindpunt en schrijft ze naar de opgegeven byte-array.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De byte-array waar de ontvangen gegevens aan worden toegewezen. |
| size | **int32_t** | Het aantal bytes dat moet worden ontvangen en dat aan de opgegeven byte-array wordt toegewezen vanaf de 'offset'-index. |
| socketFlags | [SocketFlags](../../socketflags/) | Het ontvangstgedrag. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Het externe eindpunt. |

### Retourwaarde

Het aantal ontvangen bytes.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Ontvangt gegevens van het opgegeven eindpunt en schrijft ze naar de opgegeven byte-array.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | De byte-array waar de ontvangen gegevens aan worden toegewezen. |
| size | **int32_t** | Het aantal bytes dat moet worden ontvangen en dat aan de opgegeven byte-array wordt toegewezen vanaf de 'offset'-index. |
| socketFlags | [SocketFlags](../../socketflags/) | Het ontvangstgedrag. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Het externe eindpunt. |

### Retourwaarde

Het aantal ontvangen bytes.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Ontvangt gegevens van het opgegeven eindpunt en schrijft ze naar de opgegeven byte-array.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | De byte-array waar de ontvangen gegevens aan worden toegewezen. |
| size | **int32_t** | Het aantal bytes dat moet worden ontvangen en dat aan de opgegeven byte-array wordt toegewezen vanaf de 'offset'-index. |
| socketFlags | [SocketFlags](../../socketflags/) | Het ontvangstgedrag. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Het externe eindpunt. |

### Retourwaarde

Het aantal ontvangen bytes.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Ontvangt gegevens van het opgegeven eindpunt en schrijft ze naar de opgegeven byte-array.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De byte-array waar de ontvangen gegevens aan worden toegewezen. |
| socketFlags | [SocketFlags](../../socketflags/) | Het ontvangstgedrag. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Het externe eindpunt. |

### Retourwaarde

Het aantal ontvangen bytes.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Ontvangt gegevens van het opgegeven eindpunt en schrijft ze naar de opgegeven byte-array.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | De byte-array waar de ontvangen gegevens aan worden toegewezen. |
| socketFlags | [SocketFlags](../../socketflags/) | Het ontvangstgedrag. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Het externe eindpunt. |

### Retourwaarde

Het aantal ontvangen bytes.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Ontvangt gegevens van het opgegeven eindpunt en schrijft ze naar de opgegeven byte-array.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De byte-array waar de ontvangen gegevens aan worden toegewezen. |
| socketFlags | [SocketFlags](../../socketflags/) | Het ontvangstgedrag. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Het externe eindpunt. |

### Retourwaarde

Het aantal ontvangen bytes.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) method

Ontvangt gegevens van het opgegeven eindpunt en schrijft ze naar de opgegeven byte-array.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De byte-array waar de ontvangen gegevens aan worden toegewezen. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Het externe eindpunt. |

### Retourwaarde

Het aantal ontvangen bytes.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) method

Ontvangt gegevens van het opgegeven eindpunt en schrijft ze naar de opgegeven byte-array.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | De byte-array waar de ontvangen gegevens aan worden toegewezen. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Het externe eindpunt. |

### Retourwaarde

Het aantal ontvangen bytes.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>\&) method

Ontvangt gegevens van het opgegeven eindpunt en schrijft ze naar de opgegeven byte-array.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | De byte-array waar de ontvangen gegevens aan worden toegewezen. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Het externe eindpunt. |

### Retourwaarde

Het aantal ontvangen bytes.

## Zie ook

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
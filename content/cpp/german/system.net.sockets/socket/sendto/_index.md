---
title: SendTo()
second_title: Aspose.Slides für C++ API-Referenz
description: Sendet die angegebenen Daten an den angegebenen Endpunkt.
type: docs
weight: 651
url: /de/system.net.sockets/socket/sendto/
---
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) Methode

Sendet die angegebenen Daten an den angegebenen Endpunkt.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Die zu sendenden Daten. |
| offset | **int32_t** | Der Versatz in Bytes im angegebenen Array. |
| size | **int32_t** | Die Anzahl der Bytes im angegebenen Array, beginnend beim Parameter 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Sendeverhalten. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Der entfernte Endpunkt. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) Methode

Sendet die angegebenen Daten an den angegebenen Endpunkt.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Die zu sendenden Daten. |
| offset | **int32_t** | Der Versatz in Bytes im angegebenen Array. |
| size | **int32_t** | Die Anzahl der Bytes im angegebenen Array, beginnend beim Parameter 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Sendeverhalten. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Der entfernte Endpunkt. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) Methode

Sendet die angegebenen Daten an den angegebenen Endpunkt.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Die zu sendenden Daten. |
| offset | **int32_t** | Der Versatz in Bytes im angegebenen Array. |
| size | **int32_t** | Die Anzahl der Bytes im angegebenen Array, beginnend beim Parameter 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Sendeverhalten. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Der entfernte Endpunkt. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) Methode

Sendet die angegebenen Daten an den angegebenen Endpunkt.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Die zu sendenden Daten. |
| size | **int32_t** | Die Anzahl der Bytes im angegebenen Array. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Sendeverhalten. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Der entfernte Endpunkt. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) Methode

Sendet die angegebenen Daten an den angegebenen Endpunkt.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Die zu sendenden Daten. |
| size | **int32_t** | Die Anzahl der Bytes im angegebenen Array. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Sendeverhalten. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Der entfernte Endpunkt. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) Methode

Sendet die angegebenen Daten an den angegebenen Endpunkt.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Die zu sendenden Daten. |
| size | **int32_t** | Die Anzahl der Bytes im angegebenen Array. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Sendeverhalten. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Der entfernte Endpunkt. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) Methode

Sendet die angegebenen Daten an den angegebenen Endpunkt.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Die zu sendenden Daten. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Sendeverhalten. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Der entfernte Endpunkt. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) Methode

Sendet die angegebenen Daten an den angegebenen Endpunkt.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Die zu sendenden Daten. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Sendeverhalten. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Der entfernte Endpunkt. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags, System::SharedPtr\<EndPoint\>) Methode

Sendet die angegebenen Daten an den angegebenen Endpunkt.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Die zu sendenden Daten. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Sendeverhalten. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Der entfernte Endpunkt. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>) Methode

Sendet die angegebenen Daten an den angegebenen Endpunkt.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Die zu sendenden Daten. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Der entfernte Endpunkt. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>) Methode

Sendet die angegebenen Daten an den angegebenen Endpunkt.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Die zu sendenden Daten. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Der entfernte Endpunkt. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>) Methode

Sendet die angegebenen Daten an den angegebenen Endpunkt.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> remoteEP)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Die zu sendenden Daten. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Der entfernte Endpunkt. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Siehe Auch

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
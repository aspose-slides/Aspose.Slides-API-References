---
title: ReceiveFrom()
second_title: Aspose.Slides für C++ API-Referenz
description: Empfängt Daten vom angegebenen Endpunkt und schreibt sie in das angegebene Byte-Array.
type: docs
weight: 690
url: /de/system.net.sockets/socket/receivefrom/
---
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Empfängt Daten vom angegebenen Endpunkt und schreibt sie in das angegebene Byte-Array.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Das Byte-Array, dem die empfangenen Daten zugewiesen werden. |
| offset | **int32_t** | Der Offset in Bytes im angegebenen Array. |
| size | **int32_t** | Die Anzahl der Bytes, die empfangen werden sollen und die dem angegebenen Byte-Array ab dem Index 'offset' zugewiesen werden. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Empfangsverhalten. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Der Remote-Endpunkt. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Empfängt Daten vom angegebenen Endpunkt und schreibt sie in das angegebene Byte-Array.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Das Byte-Array, dem die empfangenen Daten zugewiesen werden. |
| offset | **int32_t** | Der Offset in Bytes im angegebenen Array. |
| size | **int32_t** | Die Anzahl der Bytes, die empfangen werden sollen und die dem angegebenen Byte-Array ab dem Index 'offset' zugewiesen werden. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Empfangsverhalten. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Der Remote-Endpunkt. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Empfängt Daten vom angegebenen Endpunkt und schreibt sie in das angegebene Byte-Array.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Das Byte-Array, dem die empfangenen Daten zugewiesen werden. |
| offset | **int32_t** | Der Offset in Bytes im angegebenen Array. |
| size | **int32_t** | Die Anzahl der Bytes, die empfangen werden sollen und die dem angegebenen Byte-Array ab dem Index 'offset' zugewiesen werden. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Empfangsverhalten. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Der Remote-Endpunkt. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Empfängt Daten vom angegebenen Endpunkt und schreibt sie in das angegebene Byte-Array.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Das Byte-Array, dem die empfangenen Daten zugewiesen werden. |
| size | **int32_t** | Die Anzahl der Bytes, die empfangen werden sollen und die dem angegebenen Byte-Array ab dem Index 'offset' zugewiesen werden. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Empfangsverhalten. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Der Remote-Endpunkt. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Empfängt Daten vom angegebenen Endpunkt und schreibt sie in das angegebene Byte-Array.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Das Byte-Array, dem die empfangenen Daten zugewiesen werden. |
| size | **int32_t** | Die Anzahl der Bytes, die empfangen werden sollen und die dem angegebenen Byte-Array ab dem Index 'offset' zugewiesen werden. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Empfangsverhalten. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Der Remote-Endpunkt. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Empfängt Daten vom angegebenen Endpunkt und schreibt sie in das angegebene Byte-Array.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Das Byte-Array, dem die empfangenen Daten zugewiesen werden. |
| size | **int32_t** | Die Anzahl der Bytes, die empfangen werden sollen und die dem angegebenen Byte-Array ab dem Index 'offset' zugewiesen werden. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Empfangsverhalten. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Der Remote-Endpunkt. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Empfängt Daten vom angegebenen Endpunkt und schreibt sie in das angegebene Byte-Array.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Das Byte-Array, dem die empfangenen Daten zugewiesen werden. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Empfangsverhalten. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Der Remote-Endpunkt. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Empfängt Daten vom angegebenen Endpunkt und schreibt sie in das angegebene Byte-Array.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Das Byte-Array, dem die empfangenen Daten zugewiesen werden. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Empfangsverhalten. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Der Remote-Endpunkt. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Empfängt Daten vom angegebenen Endpunkt und schreibt sie in das angegebene Byte-Array.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Das Byte-Array, dem die empfangenen Daten zugewiesen werden. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Empfangsverhalten. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Der Remote-Endpunkt. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) method

Empfängt Daten vom angegebenen Endpunkt und schreibt sie in das angegebene Byte-Array.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Das Byte-Array, dem die empfangenen Daten zugewiesen werden. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Der Remote-Endpunkt. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) method

Empfängt Daten vom angegebenen Endpunkt und schreibt sie in das angegebene Byte-Array.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Das Byte-Array, dem die empfangenen Daten zugewiesen werden. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Der Remote-Endpunkt. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>\&) method

Empfängt Daten vom angegebenen Endpunkt und schreibt sie in das angegebene Byte-Array.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Das Byte-Array, dem die empfangenen Daten zugewiesen werden. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Der Remote-Endpunkt. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Siehe auch

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [EndPoint](../../../system.net/endpoint/)
* Klasse [Socket](../)
* Namensraum [System::Net::Sockets](../../)
* Bibliothek [Aspose.Slides](../../../)
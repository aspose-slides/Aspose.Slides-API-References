---
title: Receive()
second_title: Aspose.Slides für C++ API-Referenz
description: Empfängt Daten vom Socket und schreibt sie in das angegebene Byte-Array.
type: docs
weight: 664
url: /de/system.net.sockets/socket/receive/
---
## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) Methode

Empfängt Daten vom Socket und schreibt sie in das angegebene Byte-Array.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Das Byte-Array, in das die empfangenen Daten geschrieben werden. |
| size | **int32_t** | Die Anzahl der zu empfangenden Bytes. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Empfangsverhalten. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) Methode

Empfängt Daten vom Socket und schreibt sie in das angegebene Byte-Array.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Das Byte-Array, in das die empfangenen Daten geschrieben werden. |
| size | **int32_t** | Die Anzahl der zu empfangenden Bytes. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Empfangsverhalten. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) Methode

Empfängt Daten vom Socket und schreibt sie in das angegebene Byte-Array.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Das Byte-Array, in das die empfangenen Daten geschrieben werden. |
| size | **int32_t** | Die Anzahl der zu empfangenden Bytes. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Empfangsverhalten. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, SocketFlags) Methode

Empfängt Daten vom Socket und schreibt sie in das angegebene Byte-Array.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Das Byte-Array, in das die empfangenen Daten geschrieben werden. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Empfangsverhalten. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, SocketFlags) Methode

Empfängt Daten vom Socket und schreibt sie in das angegebene Byte-Array.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Das Byte-Array, in das die empfangenen Daten geschrieben werden. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Empfangsverhalten. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) Methode

Empfängt Daten vom Socket und schreibt sie in das angegebene Byte-Array.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Das Byte-Array, in das die empfangenen Daten geschrieben werden. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Empfangsverhalten. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Socket::Receive(System::ArrayPtr\<uint8_t\>) Methode

Empfängt Daten vom Socket und schreibt sie in das angegebene Byte-Array.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Das Byte-Array, in das die empfangenen Daten geschrieben werden. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>) Methode

Empfängt Daten vom Socket und schreibt sie in das angegebene Byte-Array.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Das Byte-Array, in das die empfangenen Daten geschrieben werden. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&) Methode

Empfängt Daten vom Socket und schreibt sie in das angegebene Byte-Array.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Das Byte-Array, in das die empfangenen Daten geschrieben werden. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) Methode

Empfängt Daten vom Socket und schreibt sie in das angegebene Byte-Array.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Das Byte-Array, in das die empfangenen Daten geschrieben werden. |
| offset | **int32_t** | Der Offset in Bytes im angegebenen Array. |
| size | **int32_t** | Die Anzahl der Bytes, die empfangen und ab dem Index 'offset' in das angegebene Byte-Array geschrieben werden. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Empfangsverhalten. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) Methode

Empfängt Daten vom Socket und schreibt sie in das angegebene Byte-Array.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Das Byte-Array, in das die empfangenen Daten geschrieben werden. |
| offset | **int32_t** | Der Offset in Bytes im angegebenen Array. |
| size | **int32_t** | Die Anzahl der Bytes, die empfangen und ab dem Index 'offset' in das angegebene Byte-Array geschrieben werden. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Empfangsverhalten. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) Methode

Empfängt Daten vom Socket und schreibt sie in das angegebene Byte-Array.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Das Byte-Array, in das die empfangenen Daten geschrieben werden. |
| offset | **int32_t** | Der Offset in Bytes im angegebenen Array. |
| size | **int32_t** | Die Anzahl der Bytes, die empfangen und ab dem Index 'offset' in das angegebene Byte-Array geschrieben werden. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Empfangsverhalten. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) Methode

Empfängt Daten vom Socket und schreibt sie in das angegebene Byte-Array.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Das Byte-Array, in das die empfangenen Daten geschrieben werden. |
| offset | **int32_t** | Der Offset in Bytes im angegebenen Array. |
| size | **int32_t** | Die Anzahl der Bytes, die empfangen und ab dem Index 'offset' in das angegebene Byte-Array geschrieben werden. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Empfangsverhalten. |
| errorCode | [SocketError](../../socketerror/)\& | Der Ausgabeparameter, in dem der Fehlercode zugewiesen wird, wenn der Empfangsvorgang fehlschlägt. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) Methode

Empfängt Daten vom Socket und schreibt sie in das angegebene Byte-Array.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Das Byte-Array, in das die empfangenen Daten geschrieben werden. |
| offset | **int32_t** | Der Offset in Bytes im angegebenen Array. |
| size | **int32_t** | Die Anzahl der Bytes, die empfangen und ab dem Index 'offset' in das angegebene Byte-Array geschrieben werden. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Empfangsverhalten. |
| errorCode | [SocketError](../../socketerror/)\& | Der Ausgabeparameter, in dem der Fehlercode zugewiesen wird, wenn der Empfangsvorgang fehlschlägt. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) Methode

Empfängt Daten vom Socket und schreibt sie in das angegebene Byte-Array.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Das Byte-Array, in das die empfangenen Daten geschrieben werden. |
| offset | **int32_t** | Der Offset in Bytes im angegebenen Array. |
| size | **int32_t** | Die Anzahl der Bytes, die empfangen und ab dem Index 'offset' in das angegebene Byte-Array geschrieben werden. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Empfangsverhalten. |
| errorCode | [SocketError](../../socketerror/)\& | Der Ausgabeparameter, in dem der Fehlercode zugewiesen wird, wenn der Empfangsvorgang fehlschlägt. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) Methode

Empfängt Daten vom Socket und schreibt sie in die angegebenen Byte-Arrays.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Die Byte-Arrays, in die die empfangenen Daten geschrieben werden. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) Methode

Empfängt Daten vom Socket und schreibt sie in die angegebenen Byte-Arrays.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Die Byte-Arrays, in die die empfangenen Daten geschrieben werden. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Empfangsverhalten. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) Methode

Empfängt Daten vom Socket und schreibt sie in die angegebenen Byte-Arrays.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Die Byte-Arrays, in die die empfangenen Daten geschrieben werden. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Empfangsverhalten. |
| errorCode | [SocketError](../../socketerror/)\& | Der Ausgabeparameter, in dem der Fehlercode zugewiesen wird, wenn der Empfangsvorgang fehlschlägt. |

### Rückgabewert

Die Anzahl der empfangenen Bytes.

## Siehe auch

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Socket](../)
* Klasse [IList](../../../system.collections.generic/ilist/)
* Klasse [ArraySegment](../../../system/arraysegment/)
* Namensraum [System::Net::Sockets](../../)
* Bibliothek [Aspose.Slides](../../../)
---
title: Send()
second_title: Aspose.Slides für C++ API Referenz
description: Sendet die angegebenen Daten an den Socket.
type: docs
weight: 638
url: /de/system.net.sockets/socket/send/
---
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) Methode

Sendet die angegebenen Daten an den Socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### Parameter
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Die zu sendenden Daten. |
| size | **int32_t** | Die Anzahl der Bytes aus den angegebenen Daten, die gesendet werden muss. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Sendeverhalten. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) Methode

Sendet die angegebenen Daten an den Socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### Parameter
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Die zu sendenden Daten. |
| size | **int32_t** | Die Anzahl der Bytes aus den angegebenen Daten, die gesendet werden muss. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Sendeverhalten. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) Methode

Sendet die angegebenen Daten an den Socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```

### Parameter
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Die zu sendenden Daten. |
| size | **int32_t** | Die Anzahl der Bytes aus den angegebenen Daten, die gesendet werden muss. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Sendeverhalten. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Socket::Send(System::ArrayPtr\<uint8_t\>, SocketFlags) Methode

Sendet die angegebenen Daten an den Socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```

### Parameter
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Die zu sendenden Daten. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Sendeverhalten. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, SocketFlags) Methode

Sendet die angegebenen Daten an den Socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```

### Parameter
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Die zu sendenden Daten. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Sendeverhalten. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) Methode

Sendet die angegebenen Daten an den Socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```

### Parameter
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Die zu sendenden Daten. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Sendeverhalten. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Socket::Send(System::ArrayPtr\<uint8_t\>) Methode

Sendet die angegebenen Daten an den Socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer)
```

### Parameter
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Die zu sendenden Daten. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Socket::Send(System::Details::ArrayView\<uint8_t\>) Methode

Sendet die angegebenen Daten an den Socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer)
```

### Parameter
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Die zu sendenden Daten. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&) Methode

Sendet die angegebenen Daten an den Socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer)
```

### Parameter
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Die zu sendenden Daten. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) Methode

Sendet die angegebenen Daten an den Socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```

### Parameter
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Eine Sammlung von Byte-Arrays, aus denen Daten gesendet werden müssen. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) Methode

Sendet die angegebenen Daten an den Socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```

### Parameter
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Eine Sammlung von Byte-Arrays, aus denen Daten gesendet werden müssen. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Sendeverhalten. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) Methode

Sendet die angegebenen Daten an den Socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```

### Parameter
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Eine Sammlung von Byte-Arrays, aus denen Daten gesendet werden müssen. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Sendeverhalten. |
| errorCode | [SocketError](../../socketerror/)\& | Der Ausgangsparameter, dem der Fehlercode zugewiesen wird, wenn der Sendevorgang fehlschlägt. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) Methode

Sendet die angegebenen Daten an den Socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Parameter
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Die zu sendenden Daten. |
| offset | **int32_t** | Der Offset in Bytes im angegebenen Array. |
| size | **int32_t** | Die Anzahl der Bytes im angegebenen Array, beginnend ab dem Parameter „offset“. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Sendeverhalten. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) Methode

Sendet die angegebenen Daten an den Socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Parameter
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Die zu sendenden Daten. |
| offset | **int32_t** | Der Offset in Bytes im angegebenen Array. |
| size | **int32_t** | Die Anzahl der Bytes im angegebenen Array, beginnend ab dem Parameter „offset“. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Sendeverhalten. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) Methode

Sendet die angegebenen Daten an den Socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Parameter
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Die zu sendenden Daten. |
| offset | **int32_t** | Der Offset in Bytes im angegebenen Array. |
| size | **int32_t** | Die Anzahl der Bytes im angegebenen Array, beginnend ab dem Parameter „offset“. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Sendeverhalten. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) Methode

Sendet die angegebenen Daten an den Socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Parameter
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Die zu sendenden Daten. |
| offset | **int32_t** | Der Offset in Bytes im angegebenen Array. |
| size | **int32_t** | Die Anzahl der Bytes im angegebenen Array, beginnend ab dem Parameter „offset“. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Sendeverhalten. |
| errorCode | [SocketError](../../socketerror/)\& | Der Ausgangsparameter, dem der Fehlercode zugewiesen wird, wenn der Sendevorgang fehlschlägt. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) Methode

Sendet die angegebenen Daten an den Socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Parameter
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Die zu sendenden Daten. |
| offset | **int32_t** | Der Offset in Bytes im angegebenen Array. |
| size | **int32_t** | Die Anzahl der Bytes im angegebenen Array, beginnend ab dem Parameter „offset“. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Sendeverhalten. |
| errorCode | [SocketError](../../socketerror/)\& | Der Ausgangsparameter, dem der Fehlercode zugewiesen wird, wenn der Sendevorgang fehlschlägt. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) Methode

Sendet die angegebenen Daten an den Socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Parameter
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Die zu sendenden Daten. |
| offset | **int32_t** | Der Offset in Bytes im angegebenen Array. |
| size | **int32_t** | Die Anzahl der Bytes im angegebenen Array, beginnend ab dem Parameter „offset“. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Sendeverhalten. |
| errorCode | [SocketError](../../socketerror/)\& | Der Ausgangsparameter, dem der Fehlercode zugewiesen wird, wenn der Sendevorgang fehlschlägt. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Siehe auch

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Socket](../)
* Klasse [IList](../../../system.collections.generic/ilist/)
* Klasse [ArraySegment](../../../system/arraysegment/)
* Namensraum [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
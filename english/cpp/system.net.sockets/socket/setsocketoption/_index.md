---
title: SetSocketOption()
second_title: Aspose.Slides for C++ API Reference
description: Sets the specified socket option to the specified value.
type: docs
weight: 716
url: /cpp/system.net.sockets/socket/setsocketoption/
---
## Socket::SetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) method


Sets the specified socket option to the specified value.

```cpp
void System::Net::Sockets::Socket::SetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionValue)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | The socket option level. |
| optionName | [SocketOptionName](../../socketoptionname/) | The name of the option that must be updated. |
| optionValue | **int32_t** | The value that must be set to the specified option. |

## Socket::SetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) method


Sets the specified socket option to the specified value.

```cpp
void System::Net::Sockets::Socket::SetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | The socket option level. |
| optionName | [SocketOptionName](../../socketoptionname/) | The name of the option that must be updated. |
| optionValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | The value that must be set to the specified option. |

## Socket::SetSocketOption(SocketOptionLevel, SocketOptionName, bool) method


Sets the specified socket option to the specified value.

```cpp
void System::Net::Sockets::Socket::SetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, bool optionValue)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | The socket option level. |
| optionName | [SocketOptionName](../../socketoptionname/) | The name of the option that must be updated. |
| optionValue | **bool** | The value that must be set to the specified option. |

## Socket::SetSocketOption(SocketOptionLevel, SocketOptionName, System::SharedPtr\<Object\>) method


Sets the specified socket option to the specified value.

```cpp
void System::Net::Sockets::Socket::SetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::SharedPtr<Object> optionValue)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | The socket option level. |
| optionName | [SocketOptionName](../../socketoptionname/) | The name of the option that must be updated. |
| optionValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | The value that must be set to the specified option. |

## See Also

* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../)
* Class [Object](../../../system/object/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
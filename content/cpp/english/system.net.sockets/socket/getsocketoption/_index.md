---
title: GetSocketOption()
second_title: Aspose.Slides for C++ API Reference
description: Returns the value that corresponds to the specified option name.
type: docs
weight: 729
url: /system.net.sockets/socket/getsocketoption/
---
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName) method


Returns the value that corresponds to the specified option name.

```cpp
System::SharedPtr<Object> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | The socket option level. |
| optionName | [SocketOptionName](../../socketoptionname/) | The option name. |

### Return Value

The value that corresponds to the specified option name.

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) method


Gets the value that corresponds to the specified option name.

```cpp
void System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | The socket option level. |
| optionName | [SocketOptionName](../../socketoptionname/) | The option name. |
| optionValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | The output parameter where the corresponding value will be assigned. |

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) method


Returns the value that corresponds to the specified option name.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionLength)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | The socket option level. |
| optionName | [SocketOptionName](../../socketoptionname/) | The option name. |
| optionLength | **int32_t** | The option length. |

### Return Value

The value that corresponds to the specified option name.

## See Also

* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Object](../../../system/object/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
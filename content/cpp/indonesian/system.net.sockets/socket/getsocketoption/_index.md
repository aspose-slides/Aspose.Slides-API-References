---
title: GetSocketOption()
second_title: Aspose.Slides untuk Referensi API C++
description: Mengembalikan nilai yang sesuai dengan nama opsi yang ditentukan.
type: docs
weight: 729
url: /id/system.net.sockets/socket/getsocketoption/
---
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName) method


Mengembalikan nilai yang sesuai dengan nama opsi yang ditentukan.

```cpp
System::SharedPtr<Object> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Level opsi socket. |
| optionName | [SocketOptionName](../../socketoptionname/) | Nama opsi. |

### Return Value

Nilai yang sesuai dengan nama opsi yang ditentukan.

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) method


Mendapatkan nilai yang sesuai dengan nama opsi yang ditentukan.

```cpp
void System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Level opsi socket. |
| optionName | [SocketOptionName](../../socketoptionname/) | Nama opsi. |
| optionValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Parameter output dimana nilai yang sesuai akan diberikan. |

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) method


Mengembalikan nilai yang sesuai dengan nama opsi yang ditentukan.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionLength)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Level opsi socket. |
| optionName | [SocketOptionName](../../socketoptionname/) | Nama opsi. |
| optionLength | **int32_t** | Panjang opsi. |

### Return Value

Nilai yang sesuai dengan nama opsi yang ditentukan.

## See Also

* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Object](../../../system/object/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
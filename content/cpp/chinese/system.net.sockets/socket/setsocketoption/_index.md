---
title: SetSocketOption()
second_title: Aspose.Slides C++ API 参考
description: 将指定的套接字选项设置为指定的值。
type: docs
weight: 716
url: /zh/system.net.sockets/socket/setsocketoption/
---
## Socket::SetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) 方法


将指定的套接字选项设置为指定的值。

```cpp
void System::Net::Sockets::Socket::SetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionValue)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | 套接字选项级别。 |
| optionName | [SocketOptionName](../../socketoptionname/) | 必须更新的选项名称。 |
| optionValue | **int32_t** | 必须设置到指定选项的值。 |

## Socket::SetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) 方法


将指定的套接字选项设置为指定的值。

```cpp
void System::Net::Sockets::Socket::SetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | 套接字选项级别。 |
| optionName | [SocketOptionName](../../socketoptionname/) | 必须更新的选项名称。 |
| optionValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 必须设置到指定选项的值。 |

## Socket::SetSocketOption(SocketOptionLevel, SocketOptionName, bool) 方法


将指定的套接字选项设置为指定的值。

```cpp
void System::Net::Sockets::Socket::SetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, bool optionValue)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | 套接字选项级别。 |
| optionName | [SocketOptionName](../../socketoptionname/) | 必须更新的选项名称。 |
| optionValue | **bool** | 必须设置到指定选项的值。 |

## Socket::SetSocketOption(SocketOptionLevel, SocketOptionName, System::SharedPtr\<Object\>) 方法


将指定的套接字选项设置为指定的值。

```cpp
void System::Net::Sockets::Socket::SetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::SharedPtr<Object> optionValue)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | 套接字选项级别。 |
| optionName | [SocketOptionName](../../socketoptionname/) | 必须更新的选项名称。 |
| optionValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 必须设置到指定选项的值。 |

## 另见

* 枚举 [SocketOptionLevel](../../socketoptionlevel/)
* 枚举 [SocketOptionName](../../socketoptionname/)
* 类型别名 [ArrayPtr](../../../system/arrayptr/)
* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [Socket](../)
* 类 [Object](../../../system/object/)
* 命名空间 [System::Net::Sockets](../../)
* 库 [Aspose.Slides](../../../)
---
title: GetSocketOption()
second_title: Aspose.Slides for C++ API 参考
description: 返回对应于指定选项名称的值。
type: docs
weight: 729
url: /zh/system.net.sockets/socket/getsocketoption/
---
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName) 方法

返回对应于指定选项名称的值。

```cpp
System::SharedPtr<Object> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | 套接字选项级别。 |
| optionName | [SocketOptionName](../../socketoptionname/) | 选项名称。 |

### 返回值

对应于指定选项名称的值。

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) 方法

获取对应于指定选项名称的值。

```cpp
void System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | 套接字选项级别。 |
| optionName | [SocketOptionName](../../socketoptionname/) | 选项名称。 |
| optionValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 输出参数，将分配对应的值。 |

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) 方法

返回对应于指定选项名称的值。

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionLength)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | 套接字选项级别。 |
| optionName | [SocketOptionName](../../socketoptionname/) | 选项名称。 |
| optionLength | **int32_t** | 选项长度。 |

### 返回值

对应于指定选项名称的值。

## 参见

* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 类 [Object](../../../system/object/)
* 类 [Socket](../)
* 命名空间 [System::Net::Sockets](../../)
* 库 [Aspose.Slides](../../../)
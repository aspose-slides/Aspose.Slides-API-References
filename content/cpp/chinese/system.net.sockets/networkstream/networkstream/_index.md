---
title: NetworkStream()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个新实例。
type: docs
weight: 170
url: /zh/system.net.sockets/networkstream/networkstream/
---
## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>) 构造函数

构造一个新实例。

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | 用于发送和接收数据的套接字。 |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, System::IO::FileAccess, bool) 构造函数

构造一个新实例。

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, System::IO::FileAccess access, bool ownsSocket)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | 用于发送和接收数据的套接字。 |
| access | [System::IO::FileAccess](../../../system.io/fileaccess/) | 指定分配给实例在指定套接字上的访问类型。 |
| ownsSocket | **bool** | 指示当值为 true 时当前实例是否获取指定套接字所有权的值。 |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, bool) 构造函数

构造一个新实例。

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, bool ownsSocket)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | 用于发送和接收数据的套接字。 |
| ownsSocket | **bool** | 指示当值为 true 时当前实例是否获取指定套接字所有权的值。 |

## 参见

* Enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../../socket/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
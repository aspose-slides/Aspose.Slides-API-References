---
title: EndReceive()
second_title: Aspose.Slides for C++ API 参考
description: 等待指定的异步接收操作完成。
type: docs
weight: 534
url: /zh/system.net.sockets/socket/endreceive/
---
## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>) 方法

等待指定的异步接收操作完成。

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 表示异步接收操作的 [IAsyncResult](../../../system/iasyncresult/) 对象。 |

### 返回值

接收到的字节数。

## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>, SocketError\&) 方法

等待指定的异步接收操作完成。

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 表示异步接收操作的 [IAsyncResult](../../../system/iasyncresult/) 对象。 |
| errorCode | [SocketError](../../socketerror/)\& | 当接收操作失败时，错误代码将被分配到的输出参数。 |

### 返回值

接收到的字节数。

## 另请参见

* 枚举 [SocketError](../../socketerror/)
* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [IAsyncResult](../../../system/iasyncresult/)
* 类 [Socket](../)
* 命名空间 [System::Net::Sockets](../../)
* 库 [Aspose.Slides](../../../)
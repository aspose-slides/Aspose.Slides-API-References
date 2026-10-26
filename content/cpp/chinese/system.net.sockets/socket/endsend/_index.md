---
title: EndSend()
second_title: Aspose.Slides C++ API 参考
description: 等待指定的异步发送操作完成。
type: docs
weight: 508
url: /zh/system.net.sockets/socket/endsend/
---
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>) 方法

等待指定的异步发送操作完成。

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 一个 [IAsyncResult](../../../system/iasyncresult/) 对象，表示异步发送操作。 |

### 返回值

已发送的字节数。

## Socket::EndSend(System::SharedPtr\<IAsyncResult\>, SocketError\&) 方法

等待指定的异步发送操作完成。

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 一个 [IAsyncResult](../../../system/iasyncresult/) 对象，表示异步发送操作。 |
| errorCode | [SocketError](../../socketerror/)\& | 当发送操作失败时，错误代码将被分配到的输出参数。 |

### 返回值

已发送的字节数。

## 另请参见

* 枚举 [SocketError](../../socketerror/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IAsyncResult](../../../system/iasyncresult/)
* 类 [Socket](../)
* 命名空间 [System::Net::Sockets](../../)
* 库 [Aspose.Slides](../../../)
---
title: EndAcceptSocket()
second_title: Aspose.Slides for C++ API 参考
description: 等待指定的异步接受操作完成。
type: docs
weight: 157
url: /zh/system.net.sockets/tcplistener/endacceptsocket/
---
## TcpListener::EndAcceptSocket(System::SharedPtr\<IAsyncResult\>) 方法

等待指定的异步接受操作完成。

```cpp
System::SharedPtr<Socket> System::Net::Sockets::TcpListener::EndAcceptSocket(System::SharedPtr<IAsyncResult> asyncResult)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 一个 [IAsyncResult](../../../system/iasyncresult/) 对象，表示一次异步接受操作。 |

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Socket](../../socket/)
* 类 [IAsyncResult](../../../system/iasyncresult/)
* 类 [TcpListener](../)
* 命名空间 [System::Net::Sockets](../../)
* 库 [Aspose.Slides](../../../)
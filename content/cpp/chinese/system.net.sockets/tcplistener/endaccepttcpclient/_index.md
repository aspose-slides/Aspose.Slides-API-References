---
title: EndAcceptTcpClient()
second_title: Aspose.Slides for C++ API 参考
description: 等待指定的异步接受操作完成。
type: docs
weight: 183
url: /zh/system.net.sockets/tcplistener/endaccepttcpclient/
---
## TcpListener::EndAcceptTcpClient(System::SharedPtr\<IAsyncResult\>) 方法

等待指定的异步接受操作完成。

```cpp
System::SharedPtr<TcpClient> System::Net::Sockets::TcpListener::EndAcceptTcpClient(System::SharedPtr<IAsyncResult> asyncResult)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 表示异步接受操作的 [IAsyncResult](../../../system/iasyncresult/) 对象。 |

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [TcpClient](../../tcpclient/)
* 类 [IAsyncResult](../../../system/iasyncresult/)
* 类 [TcpListener](../)
* 命名空间 [System::Net::Sockets](../../)
* 库 [Aspose.Slides](../../../)
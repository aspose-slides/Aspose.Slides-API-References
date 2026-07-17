---
title: BeginAcceptTcpClient()
second_title: Aspose.Slides for C++ API 参考
description: 发起异步接受操作。
type: docs
weight: 170
url: /zh/system.net.sockets/tcplistener/beginaccepttcpclient/
---
## TcpListener::BeginAcceptTcpClient(AsyncCallback, System::SharedPtr\<Object\>) 方法

发起异步接受操作。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptTcpClient(AsyncCallback callback, System::SharedPtr<Object> state)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | 当操作完成时将被调用的回调。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 用户提供的数据，用于唯一标识每个异步连接操作。 |

### 返回值

表示已发起的异步接受操作的 [IAsyncResult](../../../system/iasyncresult/) 对象。

## 参见

* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类型别名 [AsyncCallback](../../../system/asynccallback/)
* 类 [IAsyncResult](../../../system/iasyncresult/)
* 类 [Object](../../../system/object/)
* 类 [TcpListener](../)
* 命名空间 [System::Net::Sockets](../../)
* 库 [Aspose.Slides](../../../)
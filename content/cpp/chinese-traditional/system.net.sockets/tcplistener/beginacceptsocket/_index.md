---
title: BeginAcceptSocket()
second_title: Aspose.Slides for C++ API 參考
description: 啟動非同步接受作業。
type: docs
weight: 144
url: /zh-hant/system.net.sockets/tcplistener/beginacceptsocket/
---
## TcpListener::BeginAcceptSocket(AsyncCallback, System::SharedPtr\<Object\>) 方法

啟動非同步接受作業。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptSocket(AsyncCallback callback, System::SharedPtr<Object> state)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | 當作業完成時會被呼叫的回呼函式。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 使用者提供的資料，用於唯一識別每個非同步連線作業。 |

### 回傳值

[IAsyncResult](../../../system/iasyncresult/) 物件，表示已啟動的非同步接受作業。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* 類別 [IAsyncResult](../../../system/iasyncresult/)
* 類別 [Object](../../../system/object/)
* 類別 [TcpListener](../)
* 命名空間 [System::Net::Sockets](../../)
* 函式庫 [Aspose.Slides](../../../)
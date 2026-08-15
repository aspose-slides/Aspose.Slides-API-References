---
title: BeginAcceptTcpClient()
second_title: Aspose.Slides for C++ API 參考
description: 啟動非同步接受作業。
type: docs
weight: 170
url: /zh-hant/system.net.sockets/tcplistener/beginaccepttcpclient/
---
## TcpListener::BeginAcceptTcpClient(AsyncCallback, System::SharedPtr\<Object\>) 方法

啟動非同步接受作業。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptTcpClient(AsyncCallback callback, System::SharedPtr<Object> state)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | 當作業完成時將被呼叫的回呼。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 使用者提供的資料，用於唯一辨識每個非同步連接作業。 |

### 回傳值

代表已啟動之非同步接受作業的 [IAsyncResult](../../../system/iasyncresult/) 物件。

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 型別定義 [AsyncCallback](../../../system/asynccallback/)
* 類別 [IAsyncResult](../../../system/iasyncresult/)
* 類別 [Object](../../../system/object/)
* 類別 [TcpListener](../)
* 命名空間 [System::Net::Sockets](../../)
* 函式庫 [Aspose.Slides](../../../)
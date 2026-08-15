---
title: BeginGetHostAddresses()
second_title: Aspose.Slides C++ API 參考
description: 啟動一個非同步作業，以使用包含主機名稱或 IP 位址的指定字串來建立新的 IPHostEntry 類別實例。
type: docs
weight: 131
url: /zh-hant/system.net/dns/begingethostaddresses/
---
## Dns::BeginGetHostAddresses(String, AsyncCallback, System::SharedPtr\<Object\>) 方法

啟動一個非同步作業，以使用包含主機名稱或 IP 位址的指定字串來建立新的 IPHostEntry 類別 實例。

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostAddresses(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | 包含主機名稱或 IP 位址的字串。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 當作業完成時要呼叫的回呼函式。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 使用者提供的資料，用於唯一識別每個非同步作業。 |

### 傳回值

代表已啟動的非同步作業的 [IAsyncResult](../../../system/iasyncresult/) 物件。

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 型別別名 [AsyncCallback](../../../system/asynccallback/)
* 類別 [IAsyncResult](../../../system/iasyncresult/)
* 類別 [String](../../../system/string/)
* 類別 [Object](../../../system/object/)
* 類別 [Dns](../)
* 命名空間 [System::Net](../../)
* 函式庫 [Aspose.Slides](../../../)
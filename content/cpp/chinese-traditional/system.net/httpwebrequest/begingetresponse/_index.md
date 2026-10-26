---
title: BeginGetResponse()
second_title: Aspose.Slides for C++ API 參考
description: 發起對資源的非同步請求。
type: docs
weight: 495
url: /zh-hant/system.net/httpwebrequest/begingetresponse/
---
## HttpWebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) 方法

發起對資源的非同步請求。

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | 當操作完成時將被呼叫的回呼。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 使用者提供的資料，用於唯一標識每個非同步操作。 |

### 回傳值

表示已啟動非同步操作的 [IAsyncResult](../../../system/iasyncresult/) 物件。

## 參見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 型別別名 [AsyncCallback](../../../system/asynccallback/)
* 類別 [IAsyncResult](../../../system/iasyncresult/)
* 類別 [Object](../../../system/object/)
* 類別 [HttpWebRequest](../)
* 命名空間 [System::Net](../../)
* 函式庫 [Aspose.Slides](../../../)
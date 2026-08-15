---
title: BeginGetResponse()
second_title: Aspose.Slides for C++ API 參考文件
description: 發起對資源的非同步請求。
type: docs
weight: 274
url: /zh-hant/system.net/webrequest/begingetresponse/
---
## WebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) 方法

發起對資源的非同步請求。

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | 操作完成時將被呼叫的回呼函式。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 使用者提供的資料，用於唯一識別每個非同步作業。 |

### 回傳值

代表已啟動的非同步作業的 [IAsyncResult](../../../system/iasyncresult/) 物件。

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* 類別 [IAsyncResult](../../../system/iasyncresult/)
* 類別 [Object](../../../system/object/)
* 類別 [WebRequest](../)
* 命名空間 [System::Net](../../)
* 函式庫 [Aspose.Slides](../../../)
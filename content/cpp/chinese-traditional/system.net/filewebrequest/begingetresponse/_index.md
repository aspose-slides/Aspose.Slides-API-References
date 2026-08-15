---
title: BeginGetResponse()
second_title: Aspose.Slides for C++ API 參考文件
description: 對資源發起非同步請求。
type: docs
weight: 170
url: /zh-hant/system.net/filewebrequest/begingetresponse/
---
## FileWebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) 方法


對資源發起非同步請求。

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | 操作完成時要呼叫的回呼函式。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 使用者提供的資料，用於唯一識別每個非同步作業。 |

### 返回值

代表已發起的非同步作業的 [IAsyncResult](../../../system/iasyncresult/) 物件。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* 類別 [IAsyncResult](../../../system/iasyncresult/)
* 類別 [Object](../../../system/object/)
* 類別 [FileWebRequest](../)
* 命名空間 [System::Net](../../)
* 函式庫 [Aspose.Slides](../../../)
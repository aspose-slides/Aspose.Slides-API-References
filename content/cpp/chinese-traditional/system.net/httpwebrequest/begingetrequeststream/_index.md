---
title: BeginGetRequestStream()
second_title: Aspose.Slides for C++ API 參考文件
description: 啟動非同步作業以取得寫入資料至資源的串流。
type: docs
weight: 469
url: /zh-hant/system.net/httpwebrequest/begingetrequeststream/
---
## HttpWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) method


啟動非同步作業以取得寫入資料至資源的串流。

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | 在作業完成時呼叫的回呼函式。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 使用者提供的資料，用於唯一識別每個非同步作業。 |

### 返回值

一個代表已啟動非同步作業的 [IAsyncResult](../../../system/iasyncresult/) 物件。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* 類別 [IAsyncResult](../../../system/iasyncresult/)
* 類別 [Object](../../../system/object/)
* 類別 [HttpWebRequest](../)
* 命名空間 [System::Net](../../)
* Library [Aspose.Slides](../../../)
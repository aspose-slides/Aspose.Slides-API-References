---
title: BeginGetRequestStream()
second_title: Aspose.Slides for C++ API 參考文件
description: 啟動非同步作業，以取得寫入資源資料的資料流。
type: docs
weight: 300
url: /zh-hant/system.net/webrequest/begingetrequeststream/
---
## WebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) 方法


啟動非同步作業以取得寫入資源的資料流。

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | A callback to be called when the operation completes. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | User-provided data used to uniquely identify each asynchronous operation. |

### 返回值

代表已啟動非同步作業的 [IAsyncResult](../../../system/iasyncresult/) 物件。

## 參見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 型別定義 [AsyncCallback](../../../system/asynccallback/)
* 類別 [IAsyncResult](../../../system/iasyncresult/)
* 類別 [Object](../../../system/object/)
* 類別 [WebRequest](../)
* 命名空間 [System::Net](../../)
* 程式庫 [Aspose.Slides](../../../)
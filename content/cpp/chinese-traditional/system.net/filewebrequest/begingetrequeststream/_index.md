---
title: BeginGetRequestStream()
second_title: Aspose.Slides for C++ API 參考文件
description: 啟動一個非同步作業，以取得寫入資料至資源的串流。
type: docs
weight: 144
url: /zh-hant/system.net/filewebrequest/begingetrequeststream/
---
## FileWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) 方法

啟動一個非同步作業，以取得寫入資料至資源的串流。

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | 當作業完成時將被呼叫的回呼。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 使用者提供的資料，用於唯一識別每個非同步作業。 |

### 傳回值

表示已啟動非同步作業的 [IAsyncResult](../../../system/iasyncresult/) 物件。

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 型別別名 [AsyncCallback](../../../system/asynccallback/)
* 類別 [IAsyncResult](../../../system/iasyncresult/)
* 類別 [Object](../../../system/object/)
* 類別 [FileWebRequest](../)
* 命名空間 [System::Net](../../)
* 函式庫 [Aspose.Slides](../../../)
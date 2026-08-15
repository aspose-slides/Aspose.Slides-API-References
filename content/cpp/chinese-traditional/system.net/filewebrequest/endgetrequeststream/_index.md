---
title: EndGetRequestStream()
second_title: Aspose.Slides for C++ API 參考文件
description: 等待指定的非同步取得串流作業完成。
type: docs
weight: 157
url: /zh-hant/system.net/filewebrequest/endgetrequeststream/
---
## FileWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) 方法

等待指定的非同步取得串流作業完成。

```cpp
System::SharedPtr<IO::Stream> System::Net::FileWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 一個代表取得串流之非同步作業的 [IAsyncResult](../../../system/iasyncresult/) 物件。 |

### 返回值

用於寫入資料至資源的串流。

## 另請參閱

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [Stream](../../../system.io/stream/)
* 類別 [IAsyncResult](../../../system/iasyncresult/)
* 類別 [FileWebRequest](../)
* 命名空間 [System::Net](../../)
* 函式庫 [Aspose.Slides](../../../)
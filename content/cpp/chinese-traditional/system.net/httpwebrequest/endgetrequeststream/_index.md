---
title: EndGetRequestStream()
second_title: Aspose.Slides for C++ API 參考
description: 等待指定的非同步取得串流操作完成。
type: docs
weight: 482
url: /zh-hant/system.net/httpwebrequest/endgetrequeststream/
---
## HttpWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) 方法

等待指定的非同步取得串流的操作完成。

```cpp
System::SharedPtr<IO::Stream> System::Net::HttpWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 一個 [IAsyncResult](../../../system/iasyncresult/) 物件，代表取得串流的非同步操作。 |

### 傳回值

用於寫入資料至資源的串流。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Stream](../../../system.io/stream/)
* 類別 [IAsyncResult](../../../system/iasyncresult/)
* 類別 [HttpWebRequest](../)
* 命名空間 [System::Net](../../)
* Library [Aspose.Slides](../../../)
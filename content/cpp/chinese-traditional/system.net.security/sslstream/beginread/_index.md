---
title: BeginRead()
second_title: Aspose.Slides for C++ API 參考
description: 啟動非同步讀取作業。
type: docs
weight: 417
url: /zh-hant/system.net.security/sslstream/beginread/
---
## SslStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) 方法

啟動非同步讀取作業。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要從中讀取資料的位元組陣列。 |
| offset | **int32_t** | 指定陣列中以位元組為單位的偏移量。 |
| count | **int32_t** | 要讀取的位元組數量。 |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | 操作完成時將被呼叫的回呼函式。 |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 使用者提供的資料，用於唯一識別每個非同步讀取作業。 |

### 傳回值

表示已啟動非同步讀取作業的 [IAsyncResult](../../../system/iasyncresult/) 物件。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)
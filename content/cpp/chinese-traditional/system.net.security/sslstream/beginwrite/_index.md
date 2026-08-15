---
title: BeginWrite()
second_title: Aspose.Slides for C++ API 參考文檔
description: 啟動非同步寫入作業。
type: docs
weight: 443
url: /zh-hant/system.net.security/sslstream/beginwrite/
---
## SslStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) 方法

啟動非同步寫入作業。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要寫入資料的位元組陣列。 |
| offset | **int32_t** | 指定陣列中以位元組為單位的偏移量。 |
| count | **int32_t** | 要寫入的位元組數。 |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | 當操作完成時被呼叫的回呼函式。 |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 使用者提供的資料，用於唯一識別每個非同步寫入操作。 |

### 返回值

一個 [IAsyncResult](../../../system/iasyncresult/) 物件，代表已啟動的非同步寫入作業。

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 型別別名 [AsyncCallback](../../../system/asynccallback/)
* 類別 [IAsyncResult](../../../system/iasyncresult/)
* 類別 [Object](../../../system/object/)
* 類別 [SslStream](../)
* 命名空間 [System::Net::Security](../../)
* 函式庫 [Aspose.Slides](../../../)
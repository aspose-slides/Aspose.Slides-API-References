---
title: BeginRead()
second_title: Aspose.Slides for C++ API 參考
description: 啟動非同步讀取操作。
type: docs
weight: 248
url: /zh-hant/system.net.sockets/networkstream/beginread/
---
## NetworkStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) method

啟動非同步讀取操作。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 將讀取的位元組寫入的位元組陣列。 |
| offset | **int32_t** | 指定陣列中以位元組為單位的偏移量。 |
| size | **int32_t** | 要讀取的位元組數。 |
| callback | [AsyncCallback](../../../system/asynccallback/) | 操作完成時要呼叫的回呼函式。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 使用者提供的資料，用於唯一識別每個非同步讀取操作。 |

### 傳回值

代表已啟動非同步讀取操作的 [IAsyncResult](../../../system/iasyncresult/) 物件。

## 參見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 型別定義 [AsyncCallback](../../../system/asynccallback/)
* 類別 [IAsyncResult](../../../system/iasyncresult/)
* 類別 [Object](../../../system/object/)
* 類別 [NetworkStream](../)
* 命名空間 [System::Net::Sockets](../../)
* 函式庫 [Aspose.Slides](../../../)
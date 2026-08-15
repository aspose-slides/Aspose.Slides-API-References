---
title: BeginWrite()
second_title: Aspose.Slides for C++ API 參考
description: 啟動非同步寫入操作。
type: docs
weight: 274
url: /zh-hant/system.net.sockets/networkstream/beginwrite/
---
## NetworkStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) 方法

啟動非同步寫入操作。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 包含待寫入資料的緩衝區。 |
| offset | **int32_t** | 指定陣列中以位元組為單位的偏移量。 |
| size | **int32_t** | 要寫入的位元組數。 |
| callback | [AsyncCallback](../../../system/asynccallback/) | 操作完成時要呼叫的回呼。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 使用者提供的資料，用於唯一識別每個非同步寫入操作。 |

### 返回值

一個 [IAsyncResult](../../../system/iasyncresult/) 物件，代表已啟動的非同步寫入操作。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* 類別 [IAsyncResult](../../../system/iasyncresult/)
* 類別 [Object](../../../system/object/)
* 類別 [NetworkStream](../)
* 命名空間 [System::Net::Sockets](../../)
* 函式庫 [Aspose.Slides](../../../)
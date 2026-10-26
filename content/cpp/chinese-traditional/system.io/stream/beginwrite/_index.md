---
title: BeginWrite()
second_title: Aspose.Slides for C++ API 參考
description: 發起非同步寫入作業。
type: docs
weight: 170
url: /zh-hant/system.io/stream/beginwrite/
---
## Stream::BeginWrite(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) 方法

發起非同步寫入作業。

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 包含待寫入資料的緩衝區 |
| offset | int | **buffer** 中的 0 基底偏移量，指示寫入資料開始的位置 |
| count | int | 要寫入的位元組數量 |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | 操作完成時要呼叫的回呼函式 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 使用者提供的資料，用於唯一識別每個非同步寫入作業 |

### 返回值

代表已發起之非同步寫入作業的 [IAsyncResult](../../../system/iasyncresult/) 物件

## 參見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 型別別名 [AsyncCallback](../../../system/asynccallback/)
* 類別 [IAsyncResult](../../../system/iasyncresult/)
* 類別 [Object](../../../system/object/)
* 類別 [Stream](../)
* 命名空間 [System::IO](../../)
* 程式庫 [Aspose.Slides](../../../)
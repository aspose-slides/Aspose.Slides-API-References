---
title: BeginRead()
second_title: Aspose.Slides for C++ API 參考
description: 啟動非同步讀取作業。
type: docs
weight: 157
url: /zh-hant/system.io/stream/beginread/
---
## Stream::BeginRead(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) 方法

啟動非同步讀取作業。

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginRead(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 用於讀取的緩衝區 |
| offset | int | 在 **buffer** 中的零基偏移，指示開始寫入讀取資料的位置 |
| count | int | 要讀取的位元組數 |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | 操作完成時呼叫的回呼函式 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 使用者提供的資料，用於唯一識別每個非同步讀取作業 |

### 返回值

表示已啟動非同步讀取作業的 [IAsyncResult](../../../system/iasyncresult/) 物件

## 參見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 型別別名 [AsyncCallback](../../../system/asynccallback/)
* 類別 [IAsyncResult](../../../system/iasyncresult/)
* 類別 [Object](../../../system/object/)
* 類別 [Stream](../)
* 命名空間 [System::IO](../../)
* 程式庫 [Aspose.Slides](../../../)
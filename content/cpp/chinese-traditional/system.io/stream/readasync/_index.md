---
title: ReadAsync()
second_title: Aspose.Slides for C++ API 參考
description: 以非同步方式從目前的串流讀取一系列位元組，並依讀取的位元組數前進串流中的位置，且監控取消請求。
type: docs
weight: 40
url: /zh-hant/system.io/stream/readasync/
---
## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) 方法


以非同步方式從目前的串流讀取一系列位元組，並依讀取的位元組數前進串流中的位置，且監控取消請求。

```cpp
virtual RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 用於寫入已讀位元組的位元組陣列。 |
| offset | **int32_t** | 在 **buffer** 中以 0 為起點的寫入位置。 |
| count | **int32_t** | 要讀取的位元組數。 |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | 用於監控取消請求的 token。 |

### 返回值

表示非同步讀取操作的 task。TResult 參數的值包含寫入緩衝區的位元組總數。如果可用的位元組數少於請求的數量，結果值可能小於請求的位元組數，或在已達到串流結尾時為 0（零）。

## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法


以非同步方式從目前的串流讀取一系列位元組，並依讀取的位元組數前進串流中的位置，且監控取消請求。

```cpp
RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 用於寫入已讀位元組的位元組陣列。 |
| offset | **int32_t** | 在 **buffer** 中以 0 為起點的寫入位置。 |
| count | **int32_t** | 要讀取的位元組數。 |

### 返回值

表示非同步讀取操作的 task。TResult 參數的值包含寫入緩衝區的位元組總數。如果可用的位元組數少於請求的數量，結果值可能小於請求的位元組數，或在已達到串流結尾時為 0（零）。

## 另請參閱

* 型別定義 [RTaskPtr](../../../system/rtaskptr/)
* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [CancellationToken](../../../system.threading/cancellationtoken/)
* 類別 [Stream](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)
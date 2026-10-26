---
title: ReadAsync()
second_title: Aspose.Slides for C++ API 參考
description: 非同步地從目前的串流讀取一系列位元組，並依讀取的位元組數前進串流中的位置，同時監控取消請求。
type: docs
weight: 196
url: /zh-hant/system.io/filestream/readasync/
---
## FileStream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) method

非同步地從目前的串流讀取一系列位元組，並依讀取的位元組數前進串流中的位置，同時監控取消請求。

```cpp
RTaskPtr<int32_t> System::IO::FileStream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 用於寫入已讀取位元組的位元組陣列。 |
| offset | **int32_t** | 在 buffer 中的以 0 為起點的位置，作為寫入的起始點。 |
| count | **int32_t** | 要讀取的位元組數。 |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | 用於監控取消請求的 token。 |

### 返回值

表示非同步讀取作業的工作(Task)。TResult 參數的值包含寫入緩衝區的已讀取位元組總數。如果目前可用的位元組數少於請求的數量，結果值可能小於請求的位元組數；或者如果已到達串流結尾，結果值可能為 0（零）。

## 參見

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [CancellationToken](../../../system.threading/cancellationtoken/)
* 類別 [FileStream](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)
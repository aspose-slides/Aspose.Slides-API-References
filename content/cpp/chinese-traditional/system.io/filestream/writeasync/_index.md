---
title: WriteAsync()
second_title: Aspose.Slides for C++ API 參考
description: 非同步寫入一系列位元組到目前的串流，依寫入的位元組數量前進此串流中的目前位置，並監控取消請求。
type: docs
weight: 261
url: /zh-hant/system.io/filestream/writeasync/
---
## FileStream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) 方法

非同步寫入一系列位元組到目前的串流，依寫入的位元組數量前進此串流中的目前位置，並監控取消請求。

```cpp
TaskPtr System::IO::FileStream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 包含要寫入之位元組的陣列。 |
| offset | **int32_t** | 在 **buffer** 中子範圍寫入開始的 0 基索引。 |
| count | **int32_t** | 要寫入之子範圍的元素數量。 |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | 用於監控取消請求的標記。 |

### 傳回值

代表非同步寫入操作的任務。

## 另見

* 型別定義 [TaskPtr](../../../system/taskptr/)
* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [CancellationToken](../../../system.threading/cancellationtoken/)
* 類別 [FileStream](../)
* 命名空間 [System::IO](../../)
* 程式庫 [Aspose.Slides](../../../)
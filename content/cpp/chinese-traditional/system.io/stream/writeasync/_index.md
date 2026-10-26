---
title: WriteAsync()
second_title: Aspose.Slides for C++ API 參考
description: 非同步寫入位元組序列至目前的串流，並依寫入的位元組數量前進此串流中的目前位置，同時監控取消請求。
type: docs
weight: 66
url: /zh-hant/system.io/stream/writeasync/
---
## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) method


非同步寫入位元組序列至目前的串流，並依寫入的位元組數量前進此串流中的目前位置，同時監控取消要求。

```cpp
virtual TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 包含要寫入位元組的陣列。 |
| offset | **int32_t** | 在 **buffer** 中子範圍寫入開始位置的零基索引。 |
| count | **int32_t** | 子範圍中要寫入的元素數量。 |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | 用於監控取消要求的令牌。 |

### 傳回值

代表非同步寫入操作的任務。

## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


非同步寫入位元組序列至目前的串流，並依寫入的位元組數量前進此串流中的目前位置，同時監控取消要求。

```cpp
TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 包含要寫入位元組的陣列。 |
| offset | **int32_t** | 在 **buffer** 中子範圍寫入開始位置的零基索引。 |
| count | **int32_t** | 子範圍中要寫入的元素數量。 |

### 傳回值

代表非同步寫入操作的任務。

## 參見

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
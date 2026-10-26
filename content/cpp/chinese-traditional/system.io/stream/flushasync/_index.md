---
title: FlushAsync()
second_title: Aspose.Slides for C++ API 參考
description: 非同步地清除此串流的所有緩衝區，將任何緩衝資料寫入底層裝置，並監控取消請求。
type: docs
weight: 118
url: /zh-hant/system.io/stream/flushasync/
---
## Stream::FlushAsync(const Threading::CancellationToken\&) 方法

非同步地清除此串流的所有緩衝區，將任何緩衝資料寫入底層裝置，並監控取消請求。

```cpp
virtual TaskPtr System::IO::Stream::FlushAsync(const Threading::CancellationToken &cancellationToken)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | 用於監控取消請求的代幣。 |

### 返回值

表示非同步刷新操作的任務。

## Stream::FlushAsync() 方法

非同步地清除此串流的所有緩衝區，將任何緩衝資料寫入底層裝置，並監控取消請求。

```cpp
TaskPtr System::IO::Stream::FlushAsync()
```

### 返回值

表示非同步刷新操作的任務。

## 另請參閱

* 型別定義 [TaskPtr](../../../system/taskptr/)
* 類別 [CancellationToken](../../../system.threading/cancellationtoken/)
* 類別 [Stream](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)
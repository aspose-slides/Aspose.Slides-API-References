---
title: Delay()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個在時間延遲後完成的任務。
type: docs
weight: 105
url: /zh-hant/system.threading.tasks/delay/
---
## System::Threading::Tasks::Delay(int32_t) 函式

建立一個在時間延遲後完成的任務。

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | 等待多少毫秒之後完成傳回的任務，或使用 -1 表示無限等待。 |

### 返回值

代表時間延遲的任務。

## System::Threading::Tasks::Delay(int32_t, const CancellationToken\&) 函式

建立一個在時間延遲後完成且可取消的任務。

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay, const CancellationToken &cancellationToken)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | 等待多少毫秒之後完成傳回的任務，或使用 -1 表示無限等待。 |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | 可用於取消延遲的取消代碼。 |

### 返回值

代表時間延遲的任務。

## 另見

* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)
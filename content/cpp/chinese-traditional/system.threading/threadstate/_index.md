---
title: ThreadState
second_title: Aspose.Slides for C++ API 參考
description: 執行緒的狀態。
type: docs
weight: 326
url: /zh-hant/system.threading/threadstate/
---
## ThreadState 列舉

執行緒的狀態。

```cpp
enum ThreadState
```

### 值

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| Running | 0 | [Thread](../thread/) 正在執行。 |
| StopRequested | 1 | [Thread](../thread/) 停止已被請求。 |
| SuspendRequested | 2 | [Thread](../thread/) 暫停已被請求。 |
| Background | 4 | 執行緒正在背景執行。 |
| Unstarted | 8 | [Thread](../thread/) 尚未啟動。 |
| Stopped | 16 | [Thread](../thread/) 已停止。 |
| WaitSleepJoin | 32 | [Thread](../thread/) 正在等待加入。 |
| Suspended | 64 | [Thread](../thread/) 已暫停。 |
| AbortRequested | 128 | [Thread](../thread/) 中止已被請求。 |
| Aborted | 256 | [Thread](../thread/) 已中止。 |

## 另請參閱

* 命名空間 [System::Threading](../)
* 函式庫 [Aspose.Slides](../../)
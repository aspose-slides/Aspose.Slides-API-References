---
title: ThreadState
second_title: Aspose.Slides for C++ API 参考
description: 线程的状态。
type: docs
weight: 326
url: /zh/system.threading/threadstate/
---
## ThreadState 枚举

线程的状态。

```cpp
enum ThreadState
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Running | 0 | [Thread](../thread/) 正在运行. |
| StopRequested | 1 | [Thread](../thread/) 已请求停止. |
| SuspendRequested | 2 | [Thread](../thread/) 已请求挂起. |
| Background | 4 | 线程正在后台执行. |
| Unstarted | 8 | [Thread](../thread/) 未启动. |
| Stopped | 16 | [Thread](../thread/) 已停止. |
| WaitSleepJoin | 32 | [Thread](../thread/) 正在等待加入. |
| Suspended | 64 | [Thread](../thread/) 已挂起. |
| AbortRequested | 128 | [Thread](../thread/) 已请求中止. |
| Aborted | 256 | [Thread](../thread/) 已中止. |

## 另请参见

* 命名空间 [System::Threading](../)
* 库 [Aspose.Slides](../../)
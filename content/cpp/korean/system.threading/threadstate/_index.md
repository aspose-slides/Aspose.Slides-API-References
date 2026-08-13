---
title: ThreadState
second_title: Aspose.Slides for C++ API 레퍼런스
description: 스레드의 상태.
type: docs
weight: 326
url: /ko/system.threading/threadstate/
---
## ThreadState enum

스레드의 상태.

```cpp
enum ThreadState
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Running | 0 | [Thread](../thread/)이 실행 중입니다. |
| StopRequested | 1 | [Thread](../thread/) 정지 요청이 있습니다. |
| SuspendRequested | 2 | [Thread](../thread/) 일시 중단 요청이 있습니다. |
| Background | 4 | 스레드가 백그라운드에서 실행되고 있습니다. |
| Unstarted | 8 | [Thread](../thread/) 시작되지 않았습니다. |
| Stopped | 16 | [Thread](../thread/)가 중지되었습니다. |
| WaitSleepJoin | 32 | [Thread](../thread/)가 대기 중이며 조인됩니다. |
| Suspended | 64 | [Thread](../thread/)가 일시 중단되었습니다. |
| AbortRequested | 128 | [Thread](../thread/) 중단 요청이 있습니다. |
| Aborted | 256 | [Thread](../thread/)가 중단되었습니다. |

## 참조

* Namespace [System::Threading](../)
* 라이브러리 [Aspose.Slides](../../)
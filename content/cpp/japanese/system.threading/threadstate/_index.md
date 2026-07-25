---
title: ThreadState
second_title: Aspose.Slides の C++ API リファレンス
description: スレッドの状態。
type: docs
weight: 326
url: /ja/system.threading/threadstate/
---
## ThreadState 列挙体

スレッドの状態。

```cpp
enum ThreadState
```

### 列挙値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Running | 0 | [Thread](../thread/) は実行中です。 |
| StopRequested | 1 | [Thread](../thread/) の停止が要求されています。 |
| SuspendRequested | 2 | [Thread](../thread/) の一時停止が要求されています。 |
| Background | 4 | スレッドはバックグラウンドで実行されています。 |
| Unstarted | 8 | [Thread](../thread/) は開始されていません。 |
| Stopped | 16 | [Thread](../thread/) は停止しました。 |
| WaitSleepJoin | 32 | [Thread](../thread/) は結合されるのを待っています。 |
| Suspended | 64 | [Thread](../thread/) は一時停止されています。 |
| AbortRequested | 128 | [Thread](../thread/) の中止が要求されています。 |
| Aborted | 256 | [Thread](../thread/) は中止されました。 |

## 参照

* 名前空間 [System::Threading](../)
* ライブラリ [Aspose.Slides](../../)
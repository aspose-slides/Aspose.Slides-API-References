---
title: TimerQueue
second_title: Aspose.Slides for C++ API 參考
description: 處理 Timer 物件的佇列。這僅是一個實作。Timer 物件會自行註冊於此，您不需要這樣做即可使用它們——改為使用 Timer 類別 API。這是一種單例類型，記憶體管理由存取函式完成。您永遠不應直接建立它的實例。
type: docs
weight: 261
url: /zh-hant/system.threading/timerqueue/
---
## TimerQueue 類別

處理 [Timer](../timer/) 物件的佇列。這僅是一個實作。[Timer](../timer/) 物件會自行註冊於此，您不需要這樣做即可使用它們——改為使用 [Timer](../timer/) 類別 API。這是一種單例類型，記憶體管理由存取函式完成。您永遠不應直接建立它的實例。

```cpp
class TimerQueue
```

## 方法

| 方法 | 說明 |
| --- | --- |
| **bool** [Add](./add/)([Timer](../timer/) *) | 將計時器註冊至佇列。 |
| **bool** [Delete](./delete/)([Timer](../timer/) *) | 從佇列中刪除計時器。 |
| static [TimerQueue](./)\& [GetInstance](./getinstance/)() | 實作單例。 |
| static void [JoinWorkerThread](./joinworkerthread/)() | 加入工作執行緒。如有需要，會無限等待。 |
| void [operator=](./operator_equal/)(const [TimerQueue](./)\&) | 不允許複製。 |
|  [TimerQueue](./timerqueue/)(const [TimerQueue](./)\&) | 不允許複製。 |

## 另見

* 命名空間 [System::Threading](../)
* 函式庫 [Aspose.Slides](../../)
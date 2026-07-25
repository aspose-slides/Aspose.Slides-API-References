---
title: Delay()
second_title: Aspose.Slides for C++ API リファレンス
description: 遅延時間の後に完了するタスクを作成します。
type: docs
weight: 105
url: /ja/system.threading.tasks/delay/
---
## System::Threading::Tasks::Delay(int32_t) 関数


遅延時間の後に完了するタスクを作成します。

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | 返されたタスクが完了するまで待機するミリ秒数、または無期限に待機する場合は -1 を指定します。 |

### 戻り値

遅延時間を表すタスク。

## System::Threading::Tasks::Delay(int32_t, const CancellationToken\&) 関数


遅延時間の後に完了し、キャンセル可能なタスクを作成します。

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay, const CancellationToken &cancellationToken)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | 返されたタスクが完了するまで待機するミリ秒数、または無期限に待機する場合は -1 を指定します。 |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | 遅延をキャンセルするために使用できるキャンセルトークン。 |

### 戻り値

遅延時間を表すタスク。

## 参照

* 型定義 [TaskPtr](../../system/taskptr/)
* クラス [CancellationToken](../../system.threading/cancellationtoken/)
* 名前空間 [System::Threading::Tasks](../)
* ライブラリ [Aspose.Slides](../../)
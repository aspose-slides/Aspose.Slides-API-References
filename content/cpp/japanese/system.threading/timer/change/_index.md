---
title: Change()
second_title: Aspose.Slides for C++ API リファレンス
description: タイマーを再スケジュールするか、キャンセルします。
type: docs
weight: 14
url: /ja/system.threading/timer/change/
---
## Timer::Change(int64_t, int64_t) メソッド

タイマーのスケジュールを変更するか、キャンセルします。

```cpp
bool System::Threading::Timer::Change(int64_t dueTime, int64_t period)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| dueTime | **int64_t** | [Timeout](../../timeout/) 次のコールバック関数の呼び出しの前にミリ秒単位で; 負の値はタイマーがスケジュールされていてもキャンセルします。 |
| period | **int64_t** | [Timeout](../../timeout/) 連続するコールバック関数呼び出し間の間隔（ミリ秒単位）; ゼロまたは負の値はタイマーが一度だけ実行されることを意味します。 |

## Timer::Change(System::TimeSpan, System::TimeSpan) メソッド

タイマーのスケジュールを変更するか、キャンセルします。

```cpp
bool System::Threading::Timer::Change(System::TimeSpan dueTime, System::TimeSpan period)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) 次のコールバック関数の呼び出しの前に; 負の値はタイマーがスケジュールされていてもキャンセルします。 |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) 連続するコールバック関数呼び出し間の間隔; ゼロまたは負の値はタイマーが一度だけ実行されることを意味します。 |

## 参照

* クラス [Timer](../)
* クラス [TimeSpan](../../../system/timespan/)
* 名前空間 [System::Threading](../../)
* ライブラリ [Aspose.Slides](../../../)
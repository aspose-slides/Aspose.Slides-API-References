---
title: Timer()
second_title: Aspose.Slides for C++ API リファレンス
description: コンストラクタ。
type: docs
weight: 1
url: /ja/system.threading/timer/timer/
---
## Timer::Timer(TimerCallback) コンストラクタ


コンストラクタ。

```cpp
System::Threading::Timer::Timer(TimerCallback callback)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | タイマーによって呼び出される関数。 |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, int64_t, int64_t) コンストラクタ


コンストラクタ。

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, int64_t dueTime, int64_t period)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | タイマーによって呼び出される関数。 |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | コールバック関数の引数。 |
| dueTime | **int64_t** | [Timeout](../../timeout/) 最初のコールバック関数呼び出しまでのミリ秒。負の値は作成後にタイマーをスケジュールしないので、後で再スケジュールできます。 |
| period | **int64_t** | [Timeout](../../timeout/) 連続するコールバック関数呼び出し間のミリ秒単位の間隔です。非正の値はタイマーが一度だけ実行されることを意味します。 |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, System::TimeSpan, System::TimeSpan) コンストラクタ


コンストラクタ。

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, System::TimeSpan dueTime, System::TimeSpan period)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | タイマーによって呼び出される関数。 |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | コールバック関数の引数。 |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) 最初のコールバック関数呼び出しまでの時間です。負の値は作成後にタイマーをスケジュールしないので、後で再スケジュールできます。 |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) 連続するコールバック関数呼び出し間の時間です。非正の値はタイマーが一度だけ実行されることを意味します。 |

## 参照

* Typedef [TimerCallback](../../timercallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Timer](../)
* クラス [Object](../../../system/object/)
* クラス [TimeSpan](../../../system/timespan/)
* 名前空間 [System::Threading](../../)
* ライブラリ [Aspose.Slides](../../../)
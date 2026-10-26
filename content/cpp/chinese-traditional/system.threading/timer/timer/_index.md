---
title: Timer()
second_title: Aspose.Slides for C++ API 參考
description: 建構函式。
type: docs
weight: 1
url: /zh-hant/system.threading/timer/timer/
---
## Timer::Timer(TimerCallback) 建構函式

建構函式。

```cpp
System::Threading::Timer::Timer(TimerCallback callback)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | 計時器將呼叫的函式。 |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, int64_t, int64_t) 建構函式

建構函式。

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, int64_t dueTime, int64_t period)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | 計時器將呼叫的函式。 |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | 回呼函式參數。 |
| dueTime | **int64_t** | [Timeout](../../timeout/) 在第一次呼叫回呼函式之前，以毫秒為單位；負值表示在建立後不排程計時器，之後可以重新排程。 |
| period | **int64_t** | [Timeout](../../timeout/) 在回呼函式的連續呼叫之間，以毫秒為單位；非正值表示計時器僅執行一次。 |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, System::TimeSpan, System::TimeSpan) 建構函式

建構函式。

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, System::TimeSpan dueTime, System::TimeSpan period)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | 計時器將呼叫的函式。 |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | 回呼函式參數。 |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) 在第一次呼叫回呼函式之前；負值表示在建立後不排程計時器，之後可以重新排程。 |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) 在回呼函式的連續呼叫之間；非正值表示計時器僅執行一次。 |

## 另請參閱

* 類型別名 [TimerCallback](../../timercallback/)
* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Timer](../)
* 類別 [Object](../../../system/object/)
* 類別 [TimeSpan](../../../system/timespan/)
* 命名空間 [System::Threading](../../)
* 函式庫 [Aspose.Slides](../../../)
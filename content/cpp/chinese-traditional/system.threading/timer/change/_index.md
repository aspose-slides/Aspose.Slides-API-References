---
title: Change()
second_title: Aspose.Slides for C++ API 參考文件
description: 重新排程或取消計時器。
type: docs
weight: 14
url: /zh-hant/system.threading/timer/change/
---
## Timer::Change(int64_t, int64_t) 方法

重新排程或取消計時器。

```cpp
bool System::Threading::Timer::Change(int64_t dueTime, int64_t period)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| dueTime | **int64_t** | [Timeout](../../timeout/) 在下次呼叫回呼函式之前，以毫秒為單位；負值將取消計時器，即使已排程。 |
| period | **int64_t** | [Timeout](../../timeout/) 在連續呼叫回呼函式之間，以毫秒為單位；非正值表示計時器僅執行一次。 |

## Timer::Change(System::TimeSpan, System::TimeSpan) 方法

重新排程或取消計時器。

```cpp
bool System::Threading::Timer::Change(System::TimeSpan dueTime, System::TimeSpan period)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) 在下次呼叫回呼函式之前；負值將取消計時器，即使已排程。 |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) 在連續呼叫回呼函式之間；非正值表示計時器僅執行一次。 |

## 另見

* 類別 [Timer](../)
* 類別 [TimeSpan](../../../system/timespan/)
* 命名空間 [System::Threading](../../)
* 程式庫 [Aspose.Slides](../../../)
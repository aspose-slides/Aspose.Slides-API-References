---
title: WaitOne()
second_title: Aspose.Slides for C++ API 參考文件
description: 鎖定 mutex。如有需要，執行無限制等待。
type: docs
weight: 53
url: /zh-hant/system.threading/mutex/waitone/
---
## Mutex::WaitOne() 方法

鎖定 mutex。必要時執行無限制等待。

```cpp
virtual bool System::Threading::Mutex::WaitOne() override
```

### 返回值

始終返回 true，因為在 mutex 被鎖定之前不會返回。

## Mutex::WaitOne(int) 方法

鎖定 mutex。必要時執行等待。

```cpp
virtual bool System::Threading::Mutex::WaitOne(int millisecondsTimeout) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| millisecondsTimeout | int | 以毫秒為單位的等待逾時時間。 |

### 返回值

如果 mutex 已被鎖定則返回 true；如果逾時則返回 false。

## Mutex::WaitOne(TimeSpan) 方法

鎖定 mutex。必要時執行等待。

```cpp
virtual bool System::Threading::Mutex::WaitOne(TimeSpan timeout) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | 一個 [System::TimeSpan](../../../system/timespan/)，表示要等待的毫秒數，或一個 [System::TimeSpan](../../../system/timespan/)，表示 -1 毫秒，意指無限期等待。 |

### 返回值

如果 mutex 已被鎖定則返回 true；如果逾時則返回 false。

## 另請參閱

* 類別 [Mutex](../)
* 類別 [TimeSpan](../../../system/timespan/)
* 命名空間 [System::Threading](../../)
* 函式庫 [Aspose.Slides](../../../)
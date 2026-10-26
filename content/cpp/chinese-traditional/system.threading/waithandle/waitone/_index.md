---
title: WaitOne()
second_title: Aspose.Slides for C++ API 參考文件
description: 等待句柄觸發，無限期。
type: docs
weight: 27
url: /zh-hant/system.threading/waithandle/waitone/
---
## WaitHandle::WaitOne() 方法

等待句柄觸發，無限期。

```cpp
virtual bool System::Threading::WaitHandle::WaitOne()
```

### 返回值

永遠回傳 true，因為不會發生逾時。

## WaitHandle::WaitOne(int) 方法

等待句柄觸發。

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) 要等待的時間（毫秒）；-1 表示無限等待，0 表示檢查後返回，正值表示逾時。 |

### 返回值

如果句柄已觸發則為 true，若逾時則為 false。

## WaitHandle::WaitOne(TimeSpan) 方法

等待句柄觸發。

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(TimeSpan timeout)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | [System::TimeSpan](../../../system/timespan/) 代表要等待的毫秒數，或 [System::TimeSpan](../../../system/timespan/) 代表 -1 毫秒以表示無限期等待。 |

### 返回值

如果句柄已觸發則為 true，若逾時則為 false。

## WaitHandle::WaitOne(int, bool) 方法

等待句柄觸發。

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout, bool exitContext)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) 要等待的時間（毫秒）；-1 表示無限等待，0 表示檢查後返回，正值表示逾時。 |
| exitContext | **bool** | 如果為 true，等待時應在等待之前釋放對句柄的鎖定。 |

### 返回值

如果句柄已觸發則為 true，若逾時則為 false。

## 另請參閱

* 類別 [WaitHandle](../)
* 類別 [TimeSpan](../../../system/timespan/)
* 命名空間 [System::Threading](../../)
* 函式庫 [Aspose.Slides](../../../)
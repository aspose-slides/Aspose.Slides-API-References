---
title: Join()
second_title: Aspose.Slides for C++ API 參考
description: 加入受管理的執行緒。如果需要，執行無限制的等待。
type: docs
weight: 196
url: /zh-hant/system.threading/thread/join/
---
## Thread::Join() 方法


Joins managed thread. Performs unlimited waiting if required.

```cpp
void System::Threading::Thread::Join()
```

## Thread::Join(int) 方法


Joins managed thread. Performs limited waiting.

```cpp
bool System::Threading::Thread::Join(int millisecondsTimeout)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| millisecondsTimeout | int | Waiting timeout in milliseconds. |

### 返回值

True 如果執行緒成功加入，false 若逾時則返回。

## Thread::Join(TimeSpan) 方法


Joins managed thread. Performs limited waiting.

```cpp
bool System::Threading::Thread::Join(TimeSpan timeout)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | 一個 [TimeSpan](../../../system/timespan/) 設定為等待執行緒終止的時間量。 |

### 返回值

True 如果執行緒成功加入，false 若逾時則返回。

## 另請參閱

* 類別 [Thread](../)
* 類別 [TimeSpan](../../../system/timespan/)
* 命名空間 [System::Threading](../../)
* 函式庫 [Aspose.Slides](../../../)
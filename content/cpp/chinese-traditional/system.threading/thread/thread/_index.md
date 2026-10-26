---
title: Thread()
second_title: Aspose.Slides for C++ API 參考文件
description: 建構函式。
type: docs
weight: 1
url: /zh-hant/system.threading/thread/thread/
---
## Thread::Thread() 建構函式

建構函式。

```cpp
System::Threading::Thread::Thread()
```

## Thread::Thread(ThreadStart) 建構函式

建構函式。

```cpp
System::Threading::Thread::Thread(ThreadStart thread_function)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| thread_function | [ThreadStart](../../threadstart/) | 執行緒將執行的函式。 |

## Thread::Thread(ParameterizedThreadStart) 建構函式

建構函式。

```cpp
System::Threading::Thread::Thread(ParameterizedThreadStart thread_function)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| thread_function | [ParameterizedThreadStart](../../parameterizedthreadstart/) | 執行緒將執行的函式。 |

## Thread::Thread(Thread\&) 建構函式

複製建構函式。

```cpp
System::Threading::Thread::Thread(Thread &t)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| t | [Thread](../)\& | [Thread](../) 用於複製資料來源。 |

## 另請參閱

* 型別別名 [ThreadStart](../../threadstart/)
* 型別別名 [ParameterizedThreadStart](../../parameterizedthreadstart/)
* 類別 [Thread](../)
* 命名空間 [System::Threading](../../)
* 函式庫 [Aspose.Slides](../../../)